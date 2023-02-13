0-hello_World
echo 'Hello, World'
Prints followed by a new line to the standard output
1-confused_smiley
echo '"(Ôo)'\'
Displays a confused smiley
2-hellofile
cat /etc/passwd
Display content of /etc/passwd
3-twofiles
cat /etc/passwd /etc/hosts
Display the content of /etc/passwd and /etc/hosts
4-lastlines
tail /etc/passwd
Display the last 10 lines of /etc/passwd
5-firstlines
head /etc/passwd
Display the first 10 lines of /etc/passwd
6-third_line
head -3 iacta | tail -1
A script that displays the third line of the file iacta
7-file
echo "Best School" > \\\*\\\\"'\"Best School\"\\'\\\\\*$\\\?\\\*\\\*\\\*\\\*\\\*\:\)
Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8-cwd_state
ls -la > ls_cwd_content
a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
9-duplicate_last_line
tail -n 1 < iacta >> iacta
Write a script that duplicates the last line of the file iacta
10-no_more_js
find . -type f -name "*.js" -delete
 a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11-directories
find . -type d -not -name '.' | wc -l
 a script that counts the number of directories and sub-directories in the current directory.
12-newest_files
ls -t1 | head
 a script that displays the 10 newest files in the current directory.
13-unique
sort | uniq -u
 script that takes a list of words as input and prints only words that appear exactly once.
14-findthatword
grep -i "root" /etc/passwd
Display lines containing the pattern “root” from the file /etc/passwd
15-countthatword
grep -t "bin" /etc/passwd | wc -l
Display the number of lines that contain the pattern “bin” in the file /etc/passwd
16-whatsnext
grep -iA 3 "root" /etc/passwd
Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
17-hidethisword
grep -v "bin" /etc/passwd
Display all the lines in the file /etc/passwd that do not contain the pattern “bin”
18-lettersonly
grep -i '^[a-z]' /etc/ssh/sshd_config
Display all lines of the file /etc/ssh/sshd_config starting with a letter.
19-AZ
tr "A" "Z" | tr "c" "e"
Replace all characters A and c from input to Z and e respectively.
20-hiago
tr -d "cC"
 a script that removes all letters c and C from input.
21-reverse
rev
 a script that reverse its input
22-users_and_homes
cut -d ':' -f 1,6 /etc/passwd | sort
script that displays all users and their home directories, sorted by users.
100-empty_casks
find . -empty | rev | cut -d '/' -f 1 | rev
a command that finds all empty files and directories in the current directory and all sub-directories.
