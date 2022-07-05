## **file**
|Command|Argument|Action|
|-------|--------|------|-------|
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
        <tr>
            <td>-b</td>
            <td>--brief</td>
            <td>do not prepend filenames to output lines</td>
            <td></td>
        </tr>
        <tr>
            <td>-c</td>
            <td>--checking-printout</td>
            <td>print the parsed form of the magic file, use in conjunction with -m to  debug a new magic file before installing it</td>
            <td></td>
        </tr>
        <tr>
            <td>-e</td>
            <td>--exclude TEST</td>
            <td>exclude TEST from the list of test to be
                               performed for file. Valid tests are:
                               apptype, ascii, cdf, compress, csv, elf,
                               encoding, soft, tar, json, text,
                               tokens</td>
            <td></td>
        </tr>
        <tr>
            <td>-f</td>
            <td>--files-from FILE</td>
            <td>read the filenames to be examined from FILE</td>
            <td></td>
        </tr>
        <tr>
            <td>-F</td>
            <td>--separator STRING</td>
            <td>use string as separator instead of `:'</td>
            <td></td>
        </tr>
        <tr>
            <td>-i</td>
            <td>--mime</td>
            <td>output MIME type strings (--mime-type and
                               --mime-encoding)</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--apple</td>
            <td>output the Apple CREATOR/TYPE</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--extension</td>
            <td>output a slash-separated list of extensions</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--mime-type</td>
            <td>output the MIME type</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--mime-encoding</td>
            <td>output the MIME encoding</td>
            <td></td>
        </tr>
        <tr>
            <td>-k,</td>
            <td>--keep-going</td>
            <td>don't stop at the first match</td>
            <td></td>
        </tr>
        <tr>
            <td>-l</td>
            <td>--list</td>
            <td>list magic strength</td>
            <td></td>
        </tr>
        <tr>
            <td>-L</td>
            <td>--dereference</td>
            <td>follow symlinks (default if POSIXLY_CORRECT is set)</td>
            <td></td>
        </tr>
        <tr>
            <td>-h</td>
            <td>--no-dereference</td>
            <td>don't follow symlinks (default if POSIXLY_CORRECT is not set) (default)</td>
            <td></td>
        </tr>
        <tr>
            <td>-n</td>
            <td>--no-buffer</td>
            <td>do not buffer output</td>
            <td></td>
        </tr>
        <tr>
            <td>-N</td>
            <td>--no-pad</td>
            <td>do not pad output</td>
            <td></td>
        </tr>
        <tr>
            <td>-0</td>
            <td>--print0</td>
            <td>terminate filenames with ASCII NUL</td>
            <td></td>
        </tr>
        <tr>
            <td>-p</td>
            <td>--preserve-date</td>
            <td>preserve access times on files</td>
            <td></td>
        </tr>
        <tr>
            <td>-P</td>
            <td>--parameter</td>
            <td>set file engine parameter limits
                               indir        15 recursion limit for indirection
                               name         30 use limit for name/use magic
                               elf_notes   256 max ELF notes processed
                               elf_phnum   128 max ELF prog sections processed
                               elf_shnum 32768 max ELF sections processed</td>
            <td></td>
        </tr>
        <tr>
            <td>-r</td>
            <td>--raw</td>
            <td>don't translate unprintable chars to \ooo</td>
            <td></td>
        </tr>
        <tr>
            <td>-s</td>
            <td>--special-files</td>
            <td>treat special (block/char devices) files as
                             ordinary ones</td>
            <td></td>
        </tr>
        <tr>
            <td>-S</td>
            <td>--no-sandbox</td>
            <td>disable system call sandboxing</td>
            <td></td>
        </tr>
        <tr>
            <td>-C</td>
            <td>--compile</td>
            <td>compile file specified by -m</td>
            <td></td>
        </tr>
        <tr>
            <td>-d</td>
            <td>--debug</td>
            <td>print debugging messages</td>
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

> #### [GO BACK](../../annotations.md)