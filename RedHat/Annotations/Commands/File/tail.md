## **tail**

|Command|Argument|Action|
|-------|--------|------|-------|
|tail| [options] [file-path]| *Displays the content of the last number of rows (by the given number) of the file located in the given paht*|


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
            <td>tail /etc/passwd</td>
        </tr>
        <tr>
            <td>-c</td>
            <td>--bytes=[+]NUM</td>
            <td>output the last NUM bytes; or use -c +NUM to output  starting with byte NUM of each file</td>
            <td></td>
        </tr>
        <tr>
            <td>-f</td>
            <td>--follow[={name|descriptor}]</td>
            <td>output appended data as the file grows;
                             an absent option argument means 'descriptor'</td>
            <td></td>
        </tr>
        <tr>
            <td>-F</td>
            <td></td>
            <td>same as --follow=name --retry</td>
            <td></td>
        </tr>
        <tr>
            <td>-n</td>
            <td>--lines=[+]NUM</td>
            <td>output the last NUM lines, instead of the last 10; or use -n +NUM to output starting with line NUM</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--max-unchanged-stats=N</td>
            <td>with --follow=name, reopen a FILE which has not
                             changed size after N (default 5) iterations
                             to see if it has been unlinked or renamed
                             (this is the usual case of rotated log files);
                             with inotify, this option is rarely useful
                             </td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--pid=PID</td>
            <td>with -f, terminate after process ID, PID dies</td>
            <td></td>
        </tr>
        <tr>
            <td>-q,</td>
            <td>--quiet, --silent</td>
            <td>never output headers giving file names</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--retry</td>
            <td>keep trying to open a file if it is inaccessible</td>
            <td></td>
        </tr>
        <tr>
            <td>-s</td>
            <td>--sleep-interval=N</td>
            <td>with -f, sleep for approximately N seconds
                             (default 1.0) between iterations;
                             with inotify and --pid=P, check process P at
                             least once every N seconds</td>
            <td></td>
        </tr>
        <tr>
            <td>-v</td>
            <td>--verbose</td>
            <td>always output headers giving file names</td>
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

> With --follow (-f), tail defaults to following the file descriptor, which
means that even if a tail'ed file is renamed, tail will continue to track
its end.  This default behavior is not desirable when you really want to
track the actual name of the file, not the file descriptor (e.g., log
rotation).  Use --follow=name in that case.  That causes tail to track the
named file in a way that accommodates renaming, removal and creation.

---

> #### [GO BACK](../../annotations.md)