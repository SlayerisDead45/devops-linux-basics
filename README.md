# devops-linux-basics
Linux Fundamentals & DevOps Basics - Assignment 1
This repository contains the documentation and command history for the first assignment of the DevOps Masterclass. The goal of this assignment is to demonstrate proficiency in the Linux Command Line Interface (CLI), filesystem management, and basic system administration.

Task 1: File and Directory Management
Commands to create, move, and verify files.

Bash
mkdir test_dir
touch test_dir/example.txt
mv test_dir/example.txt test_dir/renamed_example.txt
ls test_dir

Task 2: Viewing System Files
Using output redirection and paging to view user databases.

Bash
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd

Task 3: Searching for Patterns
Filtering system files using regular expressions.

Bash
grep "root" /etc/passwd

Task 4: Archiving and Compression
Creating a compressed backup of a directory.

Bash
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir

Task 5: Networking and Downloads
Retrieving remote resources via the terminal.

Bash
wget https://example.com -O sample.txt

Task 6: Permissions and Security
Modifying access control levels to secure a file.

Bash
touch secure.txt
chmod 444 secure.txt
ls -l secure.txt

Task 7: Environment Variables
Setting and displaying session-specific shell variables.

export MY_VAR="Hello, Linux!"
echo $MY_VAR
Bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
