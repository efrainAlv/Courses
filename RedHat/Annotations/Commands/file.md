## **file**
|Command|Argument|Action|
|:-------:|:--------:|------|-------:|
|file| [file-path] | *Displays the file type of the file path given.* |

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
            <td>file /etc/passwd ; file /home</td>
        </tr>
        <tr>
            <td>-z</td>
            <td>--uncompress</td>
            <td>Try to look inside compressed files</td>
            <td></td>
        </tr>
        <tr>
            <td>-Z</td>
            <td>--uncompress-noreport</td>
            <td>only print the contents of compressed files</td>
            <td></td>
        </tr>
    </tbody>
</table>