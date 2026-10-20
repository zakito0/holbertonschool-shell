# Shell, I/O Redirections and Filters

This project covers standard input, standard output, standard error, redirection operators (`>`, `>>`, `<`, `<<`, `2>`, `2>&1`), pipelines (`|`), and text processing filters (`cat`, `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr`, `rev`, `cut`) in Bash on Ubuntu 20.04 LTS.

## Scripts Description

| File | Description |
| --- | --- |
| [0-hello_world](./0-hello_world) | Prints "Hello, World", followed by a new line to standard output. |
| [1-confused_smiley](./1-confused_smiley) | Displays the confused smiley `"(Ôo)'`. |
| [2-hellofile](./2-hellofile) | Displays the content of the `/etc/passwd` file. |
| [3-twofiles](./3-twofiles) | Displays the content of `/etc/passwd` and `/etc/hosts`. |
| [4-lastlines](./4-lastlines) | Displays the last 10 lines of `/etc/passwd`. |
| [5-firstlines](./5-firstlines) | Displays the first 10 lines of `/etc/passwd`. |
| [6-third_line](./6-third_line) | Displays the third line of the file `iacta`. |
| [7-file](./7-file) | Creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending with a new line. |
| [8-cwd_state](./8-cwd_state) | Writes into the file `ls_cwd_content` the result of the command `ls -la`. |
| [9-duplicate_last_line](./9-duplicate_last_line) | Duplicates the last line of the file `iacta`. |
| [10-no_more_js](./10-no_more_js) | Deletes all regular files with a `.js` extension in the current directory and all subfolders. |
| [11-directories](./11-directories) | Counts the number of directories and sub-directories in the current directory (excluding `.` and `..`). |
| [12-newest_files](./12-newest_files) | Displays the 10 newest files in the current directory, sorted from newest to oldest. |
| [13-unique](./13-unique) | Takes a list of words as input and prints only words that appear exactly once. |
| [14-findthatword](./14-findthatword) | Displays lines containing the pattern "root" from the file `/etc/passwd`. |
| [15-countthatword](./15-countthatword) | Displays the number of lines that contain the pattern "bin" in `/etc/passwd`. |
| [16-whatsnext](./16-whatsnext) | Displays lines containing the pattern "root" and 3 lines after them in `/etc/passwd`. |
| [17-hidethisword](./17-hidethisword) | Displays all lines in `/etc/passwd` that do not contain the pattern "bin". |
| [18-letteronly](./18-letteronly) | Displays all lines of `/etc/ssh/sshd_config` starting with a letter. |
| [19-AZ](./19-AZ) | Replaces all characters `A` and `c` from input to `Z` and `e` respectively. |
| [20-hiago](./20-hiago) | Removes all letters `c` and `C` from input. |
| [21-reverse](./21-reverse) | Reverses its input. |
| [22-users_and_homes](./22-users_and_homes) | Displays all users and their home directories from `/etc/passwd`, sorted by username. |
