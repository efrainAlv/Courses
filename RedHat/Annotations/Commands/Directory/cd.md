
## **cd**

|Command|Argument|Action|
|---|---|---|
|cd| [options] [directory-path] |*Switch of directory to the directory of path given.*|

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
            <td>cd /etc/</td>
        </tr>
        <tr>
            <td>-L</td>
            <td></td>
            <td>force symbolic links to be followed: resolve symbolic
                links in DIR after processing instances of `..'</td>
            <td></td>
        </tr>
        <tr>
            <td>-P</td>
            <td></td>
            <td>use the physical directory structure without following
                symbolic links: resolve symbolic links in DIR before
                processing instances of `..'</td>
            <td></td>
        </tr>
        <tr>
            <td>-e</td>
            <td></td>
            <td>if the -P option is supplied, and the current working
                directory cannot be determined successfully, exit with
                a non-zero status</td>
            <td></td>
        </tr>
        <tr>
            <td>-@</td>
            <td></td>
            <td>on systems that support it, present a file with extended
                attributes as a directory containing the file attributes
            </td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

> The variable CDPATH defines the search path for the directory containing
DIR.  Alternative directory names in CDPATH are separated by a colon (: ).
A null directory name is the same as the current directory.  If DIR begins
with a slash (/), then CDPATH is not used.

> If the directory is not found, and the shell option `cdable_vars' is set,
the word is assumed to be  a variable name.  If that variable has a value,
its value is used for DIR.
            
> The default is to follow symbolic links, as if `-L' were specified.
`..' is processed by removing the immediately previous pathname component
back to a slash or the beginning of DIR.

> **Exit Status:**
    >- Returns 0 if the directory is changed, and if $PWD is set successfully when -P is used; non-zero otherwise.

---

> #### [GO BACK](../../home.md)