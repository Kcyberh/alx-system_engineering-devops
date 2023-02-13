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
