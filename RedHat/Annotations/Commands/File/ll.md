
## **ll**
|Command|Argument|Action|
|---|---|---|
|ll| [options] [file-path]| *Displays the file information located in the given paht.*|

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
            <td>ll /etc/passwd</td>
        </tr>
        <tr>
            <td>-a</td>
            <td>--all</td>
            <td>do not ignore entries starting with .</td>
            <td></td>
        </tr>
        <tr>
            <td>-A</td>
            <td>--almost-all</td>
            <td>do not list implied . and ..</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--author</td>
            <td>with -l, print the author of each file</td>
            <td></td>
        </tr>
        <tr>
            <td>-b</td>
            <td>--escape</td>
            <td>print C-style escapes for nongraphic characters</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--block-size=SIZE</td>
            <td>with -l, scale sizes by SIZE when printing them; e.g., '--block-size=M'; see SIZE format below</td>
            <td></td>
        </tr>
        <tr>
            <td>-B</td>
            <td>--ignore-backups</td>
            <td>do not list implied entries ending with ~</td>
            <td></td>
        </tr>
        <tr>
            <td>-c</td>
            <td></td>
            <td>with -lt: sort by, and show, ctime (time of last
                               modification of file status information);
                               with -l: show ctime and sort by name;
                               otherwise: sort by ctime, newest first</td>
            <td></td>
        </tr>
        <tr>
            <td>-C</td>
            <td></td>
            <td>list entries by columns</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--color[=WHEN]</td>
            <td>colorize the output; WHEN can be 'always' (default
                               if omitted), 'auto', or 'never'; more info below</td>
            <td></td>
        </tr>
        <tr>
            <td>-d</td>
            <td>--directory</td>
            <td>list directories themselves, not their contents</td>
            <td></td>
        </tr>
        <tr>
            <td>-D</td>
            <td>--dired</td>
            <td>generate output designed for Emacs' dired mode</td>
            <td></td>
        </tr>
        <tr>
            <td>-f</td>
            <td></td>
            <td>do not sort, enable -aU, disable -ls --color</td>
            <td></td>
        </tr>
        <tr>
            <td>-F</td>
            <td>--classify</td>
            <td>append indicator (one of */=>@|) to entries</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--file-type</td>
            <td>likewise, except do not append '*'</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--format=WORD</td>
            <td>across -x, commas -m, horizontal -x, long -l, single-column -1, verbose -l, vertical -C</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--full-time</td>
            <td>like -l --time-style=full-iso</td>
            <td></td>
        </tr>
        <tr>
            <td>-g</td>
            <td></td>
            <td>like -l, but do not list owner</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--group-directories-first</td>
            <td>group directories before files; can be augmented with a --sort option, but  any use of --sort=none (-U) disables grouping</td>
            <td></td>
        </tr>
        <tr>
            <td>-G</td>
            <td>--no-group</td>
            <td>in a long listing, don't print group names</td>
            <td></td>
        </tr>
        <tr>
            <td>-h</td>
            <td>--human-readable</td>
            <td>with -l and -s, print sizes like 1K 234M 2G etc.</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--si</td>
            <td>likewise, but use powers of 1000 not 1024</td>
            <td></td>
        </tr>
        <tr>
            <td>-H</td>
            <td>--dereference-command-line</td>
            <td>follow symbolic links listed on the command line</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--dereference-command-line-symlink-to-dir</td>
            <td>follow each command line symbolic link
                               that points to a directory</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--hide=PATTERN</td>
            <td>do not list implied entries matching shell PATTERN
                               (overridden by -a or -A)</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--hyperlink[=WHEN]</td>
            <td>hyperlink file names; WHEN can be 'always'
                               (default if omitted), 'auto', or 'never'</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--indicator-style=WORD</td>
            <td>append indicator with style WORD to entry names:
                               none (default), slash (-p),
                               file-type (--file-type), classify (-F)</td>
            <td></td>
        </tr>
        <tr>
            <td>-i</td>
            <td>--inode</td>
            <td>print the index number of each file</td>
            <td></td>
        </tr>
        <tr>
            <td>-I</td>
            <td>--ignore=PATTERN</td>
            <td>do not list implied entries matching shell PATTERN</td>
            <td></td>
        </tr>
        <tr>
            <td>-k</td>
            <td>--kibibytes</td>
            <td>default to 1024-byte blocks for disk usage;
                               used only with -s and per directory totals</td>
            <td></td>
        </tr>
        <tr>
            <td>-l</td>
            <td></td>
            <td>use a long listing format</td>
            <td></td>
        </tr>
        <tr>
            <td>-L</td>
            <td>--dereference</td>
            <td>when showing file information for a symbolic
                               link, show information for the file the link
                               references rather than for the link itself</td>
            <td></td>
        </tr>
        <tr>
            <td>-m</td>
            <td></td>
            <td>fill width with a comma separated list of entries</td>
            <td></td>
        </tr>
        <tr>
            <td>-n</td>
            <td>--numeric-uid-gid</td>
            <td>like -l, but list numeric user and group IDs</td>
            <td></td>
        </tr>
        <tr>
            <td>-N</td>
            <td>--literal</td>
            <td>print entry names without quoting</td>
            <td></td>
        </tr>
        <tr>
            <td>-o</td>
            <td></td>
            <td>like -l, but do not list group information</td>
            <td></td>
        </tr>
        <tr>
            <td>-p</td>
            <td>--indicator-style=slash</td>
            <td>append / indicator to directories</td>
            <td></td>
        </tr>
        <tr>
            <td>-q</td>
            <td>--hide-control-chars</td>
            <td>print ? instead of nongraphic characters</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--show-control-chars</td>
            <td>show nongraphic characters as-is (the default,
                               unless program is 'ls' and output is a terminal)</td>
            <td></td>
        </tr>
        <tr>
            <td>-Q</td>
            <td>--quote-name</td>
            <td>enclose entry names in double quotes</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--quoting-style=WORD</td>
            <td>use quoting style WORD for entry names:
                               literal, locale, shell, shell-always,
                               shell-escape, shell-escape-always, c, escape
                               (overrides QUOTING_STYLE environment variable)</td>
            <td></td>
        </tr>
        <tr>
            <td>-r</td>
            <td>--reverse</td>
            <td>reverse order while sorting</td>
            <td></td>
        </tr>
        <tr>
            <td>-R</td>
            <td>--recursive</td>
            <td>list subdirectories recursively</td>
            <td></td>
        </tr>
        <tr>
            <td>-s</td>
            <td>--size</td>
            <td>print the allocated size of each file, in blocks</td>
            <td></td>
        </tr>
        <tr>
            <td>-S</td>
            <td></td>
            <td>sort by file size, largest first</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--sort=WORD</td>
            <td>sort by WORD instead of name: none (-U), size (-S),
                               time (-t), version (-v), extension (-X)</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--time=WORD</td>
            <td>with -l, show time as WORD instead of default
                               modification time: atime or access or use (-u);
                               ctime or status (-c); also use specified time
                               as sort key if --sort=time (newest first)</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--time-style=TIME_STYLE</td>
            <td>time/date format with -l; see TIME_STYLE below</td>
            <td></td>
        </tr>
        <tr>
            <td>-t</td>
            <td></td>
            <td>sort by modification time, newest first</td>
            <td></td>
        </tr>
        <tr>
            <td>-T</td>
            <td>--tabsize=COLS</td>
            <td>assume tab stops at each COLS instead of 8</td>
            <td></td>
        </tr>
        <tr>
            <td>-u</td>
            <td></td>
            <td>with -lt: sort by, and show, access time;
                               with -l: show access time and sort by name;
                               otherwise: sort by access time, newest first</td>
            <td></td>
        </tr>
        <tr>
            <td>-U</td>
            <td></td>
            <td>do not sort; list entries in directory order</td>
            <td></td>
        </tr>
        <tr>
            <td>-v</td>
            <td></td>
            <td>natural sort of (version) numbers within text</td>
            <td></td>
        </tr>
        <tr>
            <td>-w</td>
            <td>--width=COLS</td>
            <td>set output width to COLS.  0 means no limit</td>
            <td></td>
        </tr>
        <tr>
            <td>-x</td>
            <td></td>
            <td>list entries by lines instead of by columns</td>
            <td></td>
        </tr>
        <tr>
            <td>-X</td>
            <td></td>
            <td>sort alphabetically by entry extension</td>
            <td></td>
        </tr>
        <tr>
            <td>-Z</td>
            <td>--context</td>
            <td>print any security context of each file</td>
            <td></td>
        </tr>
        <tr>
            <td>-1</td>
            <td></td>
            <td>list one file per line.  Avoid '\n' with -q or -b</td>
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


> The SIZE argument is an integer and optional unit (example: 10K is 10*1024).
Units are K,M,G,T,P,E,Z,Y (powers of 1024) or KB,MB,... (powers of 1000).

> The TIME_STYLE argument can be full-iso, long-iso, iso, locale, or +FORMAT.
FORMAT is interpreted like in date(1).  If FORMAT is FORMAT1< newline>FORMAT2,
then FORMAT1 applies to non-recent files and FORMAT2 to recent files.
TIME_STYLE prefixed with 'posix-' takes effect only outside the POSIX locale.
Also the TIME_STYLE environment variable sets the default style to use.

> Using color to distinguish file types is disabled both by default and
with --color=never.  With --color=auto, ls emits color codes only when
standard output is connected to a terminal.  The LS_COLORS environment
variable can change the settings.  Use the dircolors command to set it.

> **Exit status**:
    >- 0  if OK,
    >- 1  if minor problems (e.g., cannot access subdirectory),
    >- 2  if serious trouble (e.g., cannot access command-line argument).


---

> #### [GO BACK](../../home.md)