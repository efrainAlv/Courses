## **head**

|Command|Argument|Action|
|---|---|---|
|head| [options] [file-path]| *Displays the content of the first number of rows (by the given number) of the file located in the given paht*|


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
            <td>Does nothing</td>
            <td>head /etc/passwd</td>
        </tr>
        <tr>
            <td>-c</td>
            <td>--bytes=[-]NUM</td>
            <td>print the first NUM bytes of each file;
                             with the leading '-', print all but the last
                             NUM bytes of each file</td>
            <td></td>
        </tr>
        <tr>
            <td>-n</td>
            <td>--lines=[-]NUM</td>
            <td>print the first NUM lines instead of the first 10;
                             with the leading '-', print all but the last
                             NUM lines of each file</td>
            <td></td>
        </tr>
        <tr>
            <td>-q</td>
            <td>--quiet, --silent</td>
            <td>never print headers giving file names</td>
            <td></td>
        </tr>
        <tr>
            <td>-v</td>
            <td>--verbose</td>
            <td>always print headers giving file names</td>
            <td></td>
        </tr>
        <tr>
            <td>-z</td>
            <td>--zero-terminated</td>
            <td>line delimiter is NUL, not newline</td>
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


> NUM may have a multiplier suffix:
b 512, kB 1000, K 1024, MB 1000*1000, M 1024*1024,
GB 1000*1000*1000, G 1024*1024*1024, and so on for T, P, E, Z, Y.


---

> #### [GO BACK](../../home.md)