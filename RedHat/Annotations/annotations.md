When a shell is used interactively, it displays a string when it is waiting for a command from the user. This is called 
the shell prompt. When a regular user starts a shell, the default prompt ends with a 
$ character, as shown below. 
            
    [user@rhel8 ~]$

---

# Estructura del sistema de archivos


![alt](./images/systemDirectories.png)

---

# Tipos de archivos

Se pueden identificar por el primer caracter con comando **ls -ld file**.

- **-** : Regular File
- **d** : Directory
- **c** : Character device file
- **b** : Block device file
- **s** : Local socket file
- **p** : Named pipe
- **l** : Symbolic link

#### Regular File 

Es el tipo mas común que se puede encontrar en el sistema Linux. Pueden considerarse arcivos comunes archivos de texto, imagenes, archivos binarios, librerias compartidas, etc. Se pueden crear archivos regulares con el comando **touch**.

    -rw-rw-r--

#### Directory

Es el segundo más comun el sistema Linux. Pueden crearse directorios con el comando **mkdir**.

    drwxrwxr-x

#### Character device

Permiten a los usuarios y programas a comunicarse con dispositivos perifericos de hardware.

    crw--------

#### Block device

Son similares a los archivos de tipo Character Device, con la diferencia que generalmente controlan el disco duro, memoria, etc.

    brw-rw-----

#### Local domain Sockets

Son usados para la comunicacion entre los procesos. Generalmente, son usados por servicios como X windows, syslog, etc. Puede ser creados por una llamada al socket system y eliminados por el **unlink** o comandos **rm**.

    srw-rw-rw-

#### Named Pipes

Similares a los Local Sockets, permiten la comunicacion entre dos procesos locales. Pueden ser creados con el comando **mknod** y removidos con el comando **rm**.

#### Symbolic Links

    lrwxrwxrwx


---

# Links

En UNIX un link es un puntero hacia un archivo.

#### Soft Links

Es un enlace que apunta al archivo original

- **¿Qué pasa si se elimina el archivo?**
    - El soft link apuntaría a nada, ya que apuntaría a un archivo inexistente.
- Puede cruzar el sistema de archivos.
- Permite vincular entre directorios.
- Tienen diferente numero de ***inodo*** y permisos que el archivo original.
- Al cambiar los permisos del archivo original, no afecta a los enalces y viceversa.

#### Hard Links

En un enlace que apunta a un copia del archivo original

- **¿Qué pasa si se elimina el archivo?**
    - El hard link seguiría apuntado al archivo con la informacion original, ya que es una copia exacta.
- No puede cruzar los limites del sistema de archivos.
- No se pueden enlazar directorios.
- Tienen el mismo numero de ***inodo*** y permisos que el archivo original.
- Al cambiar los permisos del archivo original los cambios también se reflejan en los enlaces.

---

# Commands


#### Syntaxis

- Concatenate commands with semi colon

        ;   ->  date;uptime

#### Manage Users

|Command|Argument|Action|Example|
|-------|--------|------|-------|
|useradd|user-name|*Create a new user*|```useradd user1```|
|passwd|user-name|*Change the selected user's password*|```passwd user1```|
|su| - user-name| *Switch of user. Type exit to LogOut*|```su - user1```|
|whoami||*Displays the current username*| ```whoami```|


#### Manage Files

|Command|Argument|Action|Example|
|-------|--------|------|-------|
|touch|file-name|*Creates a new file with the given name in the current directory.*|```touch file1```|
|cat|file-path|*Displays all the content of the file located in the given paht.*|```cat file1 ; cat /etc/passwd```|
|less|file-path|*Displays all the content of the file (interactively) located in the given paht.*|```less file1 ; less /etc/passwd```|
|vim| file-path | *Edit a file (interactively) located in the given paht.*| ```vim /etc/passwd```|
|ll| file-path| *Displays the file information located in the given paht.*|```ll /etc/passwd```|
|head| - number-of-rows file-path| *Displays the content of the first number of rows (by the given number) of the file located in the given paht*|```head -10 /etc/passwd```|
|tail| - number-of-rows file-path| *Displays the content of the last number of rows (by the given number) of the file located in the given paht*|```tail -10 /etc/passwd```|
|history| | *Displays the bash history*|```history```|
|pwd| |*Displays de current directory (psw = Present Working Directory)*|```pwd```|
|cd| directory-path |*Switch of directory to the directory of path given.*|```cd /etc/```|

---

## **mkdir**
|Command|Argument|Action|
|:-------:|:--------:|------|-------:|
|mkdir| [directory-path]| *Creates a new directoy with the given path* |

|Parameter|Behavior|Example|
|:-------:|:--------:|------:|
|  | Normal |``` mkdir /temp/dir1 ``` |

## **cp**
|Command|Argument|Action|
|:-------:|:--------:|------|-------:|
|cp| [oirign-file-path-1] ... [oirign-file-path-n] [destination-directory-path]| *Copia el archivo de la ruta origen la ruta del directorio destino* |

<table>
    <thead>
        <tr>
            <th colspan="2">Options</th>
            <th rowspan="2">Behavior</th>
            <th rowspan="2">Example</th>
        </tr>
        <tr>
            <th>Short</th>
            <th>Long</th>
        </tr>
    </thead>
    <tbody style="font-family: FreeMono, monospace;">
        <tr>
            <td></td>
            <td></td>
            <td>Normal</td>
            <td>cp /temp/direct1/file1 /temp/direct2/direct3/</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td>Normal</td>
            <td>cp  file1.txt file2.txt file3.txt  direct2/direct3/</td>
        </tr>
        <tr>
            <td></td>
            <td>-r</td>
            <td>Recursivo</td>
            <td>cp -r /temp/files1 /temp/files2</td>
        </tr>
    </tbody>
</table>

---