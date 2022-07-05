
## **history**

|Command|Argument|Action|
|---|---|---|
|history| [options] | *Displays the bash history*|

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
            <td>history</td>
        </tr>
        <tr>
            <td>-a</td>
            <td></td>
            <td>change only the access time</td>
            <td></td>
        </tr>
        <tr>
            <td>-c</td>
            <td></td>
            <td>clear the history list by deleting all of the entries</td>
            <td></td>
        </tr>
        <tr>
            <td>-d</td>
            <td></td>
            <td>offset delete the history entry at position OFFSET. Negative
                offsets count back from the end of the history list</td>
            <td></td>
        </tr>
        <tr>
            <td>-a</td>
            <td></td>
            <td>append history lines from this session to the history file</td>
            <td></td>
        </tr>
        <tr>
            <td>-n</td>
            <td></td>
            <td>read all history lines not already read from the history file
                and append them to the history list</td>
            <td></td>
        </tr>
        <tr>
            <td>-r</td>
            <td></td>
            <td>read the history file and append the contents to the history
                list</td>
            <td></td>
        </tr>
        <tr>
            <td>-w</td>
            <td></td>
            <td>write the current history to the history file</td>
            <td></td>
        </tr>
        <tr>
            <td>-p</td>
            <td></td>
            <td>perform history expansion on each ARG and display the result
                without storing it in the history list</td>
            <td></td>
        </tr>
        <tr>
            <td>-s</td>
            <td></td>
            <td>append the ARGs to the history list as a single entry</td>
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

>If FILENAME is given, it is used as the history file.  Otherwise,
if HISTFILE has a value, that is used, else ~/.bash_history.

>If the HISTTIMEFORMAT variable is set and not null, its value is used
as a format string for strftime(3) to print the time stamp associated
with each displayed history entry.  No time stamps are printed otherwise.


---

> #### [GO BACK](../../home.md)