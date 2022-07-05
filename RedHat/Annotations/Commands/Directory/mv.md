
## mv

|Command|Argument|Action|
|---|---|---|
|mv|[OPTION]... [-T] SOURCE DEST|*Moves one directory to another.*|
|mv|[OPTION]... SOURCE... DIRECTORY|*Moves one directory to another.*|
|mv|[OPTION]... -t DIRECTORY SOURCE...|*Moves one directory to another.*|
|mv|[OPTION]... -t DIRECTORY SOURCE...|*Moves one directory to another.*|

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
            <td>mv direct1/myFile.txt direct2/myFile.txt</td>
        </tr>
        <tr>
            <td></td>
            <td>--backup[=CONTROL]</td>
            <td>make a backup of each existing destination file</td>
            <td></td>
        </tr>
        <tr>
            <td>-b</td>
            <td></td>
            <td>like --backup but does not accept an argument</td>
            <td></td>
        </tr>
        <tr>
            <td>-f</td>
            <td>--force</td>
            <td>do not prompt before overwriting</td>
            <td></td>
        </tr>
        <tr>
            <td>-i</td>
            <td>--interactive</td>
            <td>prompt before overwrite</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--strip-trailing-slashes</td>
            <td>remove any trailing slashes from each SOURCE argument</td>
            <td></td>
        </tr>
        <tr>
            <td>-S</td>
            <td>--suffix=SUFFIX</td>
            <td>override the usual backup suffix</td>
            <td></td>
        </tr>
        <tr>
            <td>-t</td>
            <td>--target-directory=DIRECTORY</td>
            <td>move all SOURCE arguments into DIRECTORY</td>
            <td></td>
        </tr>
        <tr>
            <td>-T</td>
            <td>--no-target-directory</td>
            <td>treat DEST as a normal file</td>
            <td></td>
        </tr>
        <tr>
            <td>-u</td>
            <td>--update</td>
            <td>move only when the SOURCE file is newer than the destination file or when the destination file is missing</td>
            <td></td>
        </tr>
        <tr>
            <td>-v</td>
            <td>--verbose</td>
            <td>explain what is being done</td>
            <td></td>
        </tr>
        <tr>
            <td>-Z</td>
            <td>--context</td>
            <td>set SELinux security context of destination file to default type</td>
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

>If you specify more than one of -i, -f, -n, only the final one takes effect.

>The backup suffix is '~', unless set with --suffix or SIMPLE_BACKUP_SUFFIX.
 The version control method may be selected via the --backup option or through the VERSION_CONTROL environment variable.  Here are the values:
  >>none, off never make backups (even if --backup is given)
    numbered, t make numbered backups
    existing, nil numbered if numbered backups exist, simple otherwise
    simple, never always make simple backups


---

> #### [GO BACK](../../home.md)