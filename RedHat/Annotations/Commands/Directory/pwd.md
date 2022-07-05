
## **pwd**

|Command|Argument|Action|
|-------|--------|------|-------|
|pwd| [options] |*Displays de current directory (psw = Present Working Directory)*|

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
            <td>pwd</td>
        </tr>
        <tr>
            <td>-L</td>
            <td></td>
            <td>print the value of $PWD if it names the current working
                directory</td>
            <td></td>
        </tr>
        <tr>
            <td>-P</td>
            <td></td>
            <td>print the physical directory, without any symbolic links</td>
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

> By default, `pwd' behaves as if `-L' were specified.

> **Exit Status**:
    >- Returns 0 unless an invalid option is given or the current directory
    > -cannot be read.


---

> #### [GO BACK](../../annotations.md)