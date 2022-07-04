
## **vim**

|Command|Argument|Action|
|:-------:|:--------:|------|-------:|
|vim| [options] [file-path...] | *Edit a file (interactively) located in the given paht.*|

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
            <td>--</td>
            <td>Only file names after this</td>
            <td>vim -- /temp/file.txt</td>
        </tr>
        <tr>
            <td>-v</td>
            <td></td>
            <td>Vi mode (like "vi")</td>
            <td></td>
        </tr>
        <tr>
            <td>-e</td>
            <td></td>
            <td>Ex mode (like "ex")</td>
            <td></td>
        </tr>
        <tr>
            <td>-E</td>
            <td></td>
            <td>Improved Ex mode</td>
            <td></td>
        </tr>
        <tr>
            <td>-s</td>
            <td></td>
            <td>Silent (batch) mode (only for "ex")</td>
            <td></td>
        </tr>
        <tr>
            <td>-d</td>
            <td></td>
            <td>Diff mode (like "vimdiff")</td>
            <td></td>
        </tr>
        <tr>
            <td>-y</td>
            <td></td>
            <td>Easy mode (like "evim", modeless)</td>
            <td></td>
        </tr>
        <tr>
            <td>-R</td>
            <td></td>
            <td>Readonly mode (like "view")</td>
            <td></td>
        </tr>
        <tr>
            <td>-Z</td>
            <td></td>
            <td>Restricted mode (like "rvim")</td>
            <td></td>
        </tr>
        <tr>
            <td>-m</td>
            <td></td>
            <td>Modifications (writing files) not allowed</td>
            <td></td>
        </tr>
        <tr>
            <td>-M</td>
            <td></td>
            <td>Modifications in text not allowed</td>
            <td></td>
        </tr>
        <tr>
            <td>-b</td>
            <td></td>
            <td>Binary mode</td>
            <td></td>
        </tr>
        <tr>
            <td>-l</td>
            <td></td>
            <td>Lisp mode</td>
            <td></td>
        </tr>
        <tr>
            <td>-C</td>
            <td></td>
            <td>Compatible with Vi: 'compatible'</td>
            <td></td>
        </tr>
        <tr>
            <td>-N</td>
            <td></td>
            <td>Not fully Vi compatible: 'nocompatible'</td>
            <td></td>
        </tr>
        <tr>
            <td>-V[N][fname]</td>
            <td></td>
            <td>Be verbose [level N] [log messages to fname]</td>
            <td></td>
        </tr>
        <tr>
            <td>-D</td>
            <td>Debugging mode</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>-n</td>
            <td></td>
            <td>No swap file, use memory only</td>
            <td></td>
        </tr>
        <tr>
            <td>-r</td>
            <td></td>
            <td>List swap files and exit</td>
            <td></td>
        </tr>
        <tr>
            <td>-r (with file name)</td>
            <td></td>
            <td>Recover crashed session</td>
            <td></td>
        </tr>
        <tr>
            <td>-L</td>
            <td></td>
            <td>Same as -r</td>
            <td></td>
        </tr>
        <tr>
            <td>-A</td>
            <td></td>
            <td>Start in Arabic mode</td>
            <td></td>
        </tr>
        <tr>
            <td>-H</td>
            <td></td>
            <td>Start in Hebrew mode</td>
            <td></td>
        </tr>
        <tr>
            <td>-T <terminal></td>
            <td></td>
            <td>Set terminal type to <terminal></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--not-a-term</td>
            <td>Skip warning for input/output not being a terminal</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--ttyfail</td>
            <td>Exit if input or output is not a terminal</td>
            <td></td>
        </tr>
        <tr>
            <td>-u <vimrc></td>
            <td></td>
            <td>Use < vimrc> instead of any .vimrc</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--noplugin</td>
            <td>Don't load plugin scripts</td>
            <td></td>
        </tr>
        <tr>
            <td>-p[N]</td>
            <td></td>
            <td>Open N tab pages (default: one for each file)</td>
            <td></td>
        </tr>
        <tr>
            <td>-o[N]</td>
            <td></td>
            <td>Open N windows (default: one for each file)</td>
            <td></td>
        </tr>
        <tr>
            <td>-O[N] </td>
            <td></td>
            <td>Like -o but split vertically</td>
            <td></td>
        </tr>
        <tr>
            <td>+</td>
            <td></td>
            <td>Start at end of file</td>
            <td></td>
        </tr>
        <tr>
            <td>+< lnum></td>
            <td></td>
            <td>Start at line < lnum></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--cmd < command> </td>
            <td>Execute < command> before loading any vimrc file</td>
            <td></td>
        </tr>
        <tr>
            <td>-c < command></td>
            <td></td>
            <td>Execute <command> after loading the first file</td>
            <td></td>
        </tr>
        <tr>
            <td>-S <session> </td>
            <td></td>
            <td>Source file <session> after loading the first file</td>
            <td></td>
        </tr>
        <tr>
            <td>-s <scriptin></td>
            <td></td>
            <td>Read Normal mode commands from file <scriptin></td>
            <td></td>
        </tr>
        <tr>
            <td>-w <scriptout> </td>
            <td></td>
            <td>Append all typed commands to file <scriptout></td>
            <td></td>
        </tr>
        <tr>
            <td>-W <scriptout></td>
            <td></td>
            <td>Write all typed commands to file <scriptout></td>
            <td></td>
        </tr>
        <tr>
            <td>-x </td>
            <td></td>
            <td>Edit encrypted files</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--startuptime <file></td>
            <td>Write startup timing messages to <file></td>
            <td></td>
        </tr>
        <tr>
            <td>-i <viminfo></td>
            <td></td>
            <td>Use <viminfo> instead of .viminfo</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--clean</td>
            <td>'nocompatible', Vim defaults, no plugins, no viminfo</td>
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