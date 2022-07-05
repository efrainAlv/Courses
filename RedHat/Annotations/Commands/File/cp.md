
## **mkdir**

|Command|Argument|Action|
|-------|--------|------|-------|
|cp| [options] [oirign-file-path-1] ... [oirign-file-path-n] [destination-directory-path]| *Copia el archivo de la ruta origen la ruta del directorio destino* |

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
            <td>cp /temp/direct1/file1 /temp/direct2/direct3/</td>
        </tr>
        <tr>
            <td>-a</td>
            <td>--archive</td>
            <td>same as -dR --preserve=all</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--attributes-only</td>
            <td>don't copy the file data, just the attributes</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--backup[=CONTROL]</td>
            <td>make a backup of each existing destination file</td>
            <td></td>
        </tr>
        <tr>
            <td>-b</td>
            <td></td>
            <td>like --backup but does not accept an argument</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--copy-contents</td>
            <td>copy contents of special files when recursive</td>
            <td></td>
        </tr>
        <tr>
            <td>-d</td>
            <td></td>
            <td>same as --no-dereference --preserve=links</td>
            <td></td>
        </tr>
        <tr>
            <td>-f</td>
            <td>--force</td>
            <td>if an existing destination file cannot be
                                 opened, remove it and try again (this option
                                 is ignored when the -n option is also used)</td>
            <td></td>
        </tr>
        <tr>
            <td>-i</td>
            <td>--interactive</td>
            <td>prompt before overwrite (overrides a previous -n
                                  option)</td>
            <td></td>
        </tr>
        <tr>
            <td>-H</td>
            <td></td>
            <td>follow command-line symbolic links in SOURCE</td>
            <td></td>
        </tr>
        <tr>
            <td>-l</td>
            <td>--link</td>
            <td>hard link files instead of copying</td>
            <td></td>
        </tr>
        <tr>
            <td>-L</td>
            <td>--dereference</td>
            <td>always follow symbolic links in SOURCE</td>
            <td></td>
        </tr>
        <tr>
            <td>-n</td>
            <td>--no-clobber</td>
            <td>do not overwrite an existing file (overrides
                                 a previous -i option)</td>
            <td></td>
        </tr>
        <tr>
            <td>-P</td>
            <td>--no-dereference</td>
            <td>never follow symbolic links in SOURCE</td>
            <td></td>
        </tr>
        <tr>
            <td>-p</td>
            <td></td>
            <td>same as --preserve=mode,ownership,timestamps</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--preserve[=ATTR_LIST]</td>
            <td>preserve the specified attributes (default:
                                 mode,ownership,timestamps), if possible
                                 additional attributes: context, links, xattr,
                                 all</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--no-preserve=ATTR_LIST</td>
            <td>don't preserve the specified attributes</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--parents</td>
            <td>use full source file name under DIRECTORY</td>
            <td></td>
        </tr>
        <tr>
            <td>-R, -r</td>
            <td>--recursive</td>
            <td>copy directories recursively</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--reflink[=WHEN]</td>
            <td>control clone/CoW copies. See below</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--remove-destination</td>
            <td>remove each existing destination file before
                                 attempting to open it (contrast with --force)</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--sparse=WHEN</td>
            <td>control creation of sparse files. See below</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--strip-trailing-slashes</td>
            <td>remove any trailing slashes from each SOURCE
                                 argument</td>
            <td></td>
        </tr>
        <tr>
            <td>-s</td>
            <td>--symbolic-link</td>
            <td>make symbolic links instead of copying</td>
            <td></td>
        </tr>
        <tr>
            <td>-S</td>
            <td>--suffix=SUFFIX</td>
            <td>override the usual backup suffix</td>
            <td></td>
        </tr>
        <tr>
            <td>-t</td>
            <td>--target-directory=DIRECTORY</td>
            <td>copy all SOURCE arguments into DIRECTORY</td>
            <td></td>
        </tr>
        <tr>
            <td>-T</td>
            <td>--no-target-directory</td>
            <td>treat DEST as a normal file</td>
            <td></td>
        </tr>
        <tr>
            <td>-u</td>
            <td>--update</td>
            <td>copy only when the SOURCE file is newer
                                 than the destination file or when the
                                 destination file is missing</td>
            <td></td>
        </tr>
        <tr>
            <td>-v</td>
            <td>--verbose</td>
            <td>explain what is being done</td>
            <td></td>
        </tr>
        <tr>
            <td>-x</td>
            <td>--one-file-system</td>
            <td>stay on this file system</td>
            <td></td>
        </tr>
        <tr>
            <td>-Z</td>
            <td></td>
            <td>set SELinux security context of destination
                                 file to default type</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>--context[=CTX]</td>
            <td>like -Z, or if CTX is specified then set the
                                 SELinux or SMACK security context to CTX</td>
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

> By default, sparse SOURCE files are detected by a crude heuristic and the
corresponding DEST file is made sparse as well.  That is the behavior
selected by --sparse=auto.  Specify --sparse=always to create a sparse DEST
file whenever the SOURCE file contains a long enough sequence of zero bytes.
Use --sparse=never to inhibit creation of sparse files.

> When --reflink[=always] is specified, perform a lightweight copy, where the
data blocks are copied only when modified.  If this is not possible the copy
fails, or if --reflink=auto is specified, fall back to a standard copy.
Use --reflink=never to ensure a standard copy is performed.

> The backup suffix is '~', unless set with --suffix or SIMPLE_BACKUP_SUFFIX.
The version control method may be selected via the --backup option or through
the VERSION_CONTROL environment variable.  Here are the values:
>-  none, off       never make backups (even if --backup is given)
    numbered, t     make numbered backups
    existing, nil   numbered if numbered backups exist, simple otherwise
    simple, never   always make simple backups

> As a special case, cp makes a backup of SOURCE when the force and backup
options are given and SOURCE and DEST are the same name for an existing,
regular file.

---

> #### [GO BACK](../../annotations.md)