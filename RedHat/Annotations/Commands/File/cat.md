
## **cat**
|Command|Argument|Action|
|---|---|---|
|cat|file-path|*Displays all the content of the file located in the given paht.*|

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
            <td>cat file1 ; cat /etc/passwd</td>
        </tr>
        <tr>
            <td>-A</td>
            <td>--show-all</td>
            <td>equivalent to -vET</td>
            <td></td>
        </tr>
        <tr>
            <td>-b</td>
            <td>--number-nonblank</td>
            <td>number nonempty output lines, overrides -n</td>
            <td></td>
        </tr>
        <tr>
            <td>-e</td>
            <td></td>
            <td>equivalent to -v</td>
            <td></td>
        </tr>
        <tr>
            <td>-E</td>
            <td>--show-ends</td>
            <td>display $ at end of each line</td>
            <td></td>
        </tr>
        <tr>
            <td>-n</td>
            <td>--number</td>
            <td>number all output lines</td>
            <td></td>
        </tr>
        <tr>
            <td>-s</td>
            <td>--squeeze-blank</td>
            <td>suppress repeated empty output lines</td>
            <td></td>
        </tr>
        <tr>
            <td>-t</td>
            <td></td>
            <td>equivalent to -vT</td>
            <td></td>
        </tr>
        <tr>
            <td>-T</td>
            <td>--show-tabs</td>
            <td>display TAB characters as ^I</td>
            <td></td>
        </tr>
        <tr>
            <td>-u</td>
            <td></td>
            <td>(ignored)</td>
            <td></td>
        </tr>
        <tr>
            <td>-v</td>
            <td>--show-nonprinting</td>
            <td>use ^ and M- notation, except for LFD and TAB</td>
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


> **Examples**:
    cat f - g  Output f's contents, then standard input, then g's contents.
    cat        Copy standard input to standard output.

---

> #### [GO BACK](../../home.md)