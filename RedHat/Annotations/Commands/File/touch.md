
## **touch**
|Command|Argument|Action|
|-------|--------|------|-------|
|touch|file-name|*Creates a new file with the given name in the current directory.*|

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
            <td>touch file1</td>
        </tr>
        <tr>
            <td>-a</td>
            <td></td>
            <td>change only the access time</td>
            <td></td>
        </tr>
        <tr>
            <td>-c</td>
            <td>--no-create</td>
            <td>do not create any files</td>
            <td></td>
        </tr>
        <tr>
            <td>-d</td>
            <td>--date=STRING</td>
            <td>parse STRING and use it instead of current time</td>
            <td></td>
        </tr>
        <tr>
            <td>-f</td>
            <td></td>
            <td>(ignored)</td>
            <td></td>
        </tr>
        <tr>
            <td>-h</td>
            <td>--no-dereference</td>
            <td>affect each symbolic link instead of any referenced file (useful only on systems that can change the timestamps of a symlink)</td>
            <td></td>
        </tr>
        <tr>
            <td>-m</td>
            <td></td>
            <td>change only the modification time</td>
            <td></td>
        </tr>
        <tr>
            <td>-r</td>
            <td>--reference=FILE</td>
            <td>use this file's times instead of current time</td>
            <td></td>
        </tr>
        <tr>
            <td>-t STAMP</td>
            <td></td>
            <td>use [[CC]YY]MMDDhhmm[.ss] instead of current time</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--time=WORD</td>
            <td>
                change the specified time:
                WORD is access, atime, or use: equivalent to -a
                WORD is modify or mtime: equivalent to -m
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


> Note that the -d and -t options accept different time-date formats.

---

> #### [GO BACK](../../annotations.md)