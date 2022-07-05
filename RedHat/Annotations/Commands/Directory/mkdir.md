
## **mkdir**

|Command|Argument|Action|
|---|---|---|
|mkdir| [options] directory-path| *Creates a new directoy with the given path* |

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
            <td>mkdir /temp/newDir/</td>
        </tr>
        <tr>
            <td>-m</td>
            <td>--mode=MODE</td>
            <td>set file mode (as in chmod), not a=rwx - umask</td>
            <td></td>
        </tr>
        <tr>
            <td>-p</td>
            <td>--parents</td>
            <td>no error if existing, make parent directories as needed</td>
            <td></td>
        </tr>
        <tr>
            <td>-v</td>
            <td>--verbose</td>
            <td>print a message for each created directory</td>
            <td></td>
        </tr>
        <tr>
            <td>-Z</td>
            <td></td>
            <td>set SELinux security context of each created directory
                         to the default type</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--context[=CTX]</td>
            <td>like -Z, or if CTX is specified then set the SELinux
                         or SMACK security context to CTX</td>
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


---

> #### [GO BACK](../../home.md)