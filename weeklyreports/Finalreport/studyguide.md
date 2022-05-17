
# Study Guide for Final Spring Spring 22
## Name: Azucena Amez 

List of Commands:
# Command name: 
.date
## Description
.Display date and time in the given format.
## Syntax 
.date option + format
## Example 


# Command name: 
.uname 
## Description
.This prints system information.
## Syntax 
uname [option]
## Example 
uname -a
uname -r
uanme -m

# Command name: 
.du
## Description
.Summarize device usage of the set of Files, recursively for directories. 
## Syntax 
du [OPTION].....[File]
## Example 
.du -h /home/cis106/Downloads
.du -a -h /home/cis106/Downloads 

# Command name: 
.free
## Description
.free displays the total amount of free memory in the system. 
## Syntax 
free[options]
## Example 
. free -h
. free -b

# Command name: 
echo 
## Description
.Display a line of text 
## Syntax 
.echo [SHORT-OPTION]
## Example 
.echo -e 'Hello, \tGPU!'

# Command name: 
apt
## Description
.apt is a command for installing, updating, removing and otherwise managing deb packages on Ubuntu and Debian. 
## Syntax 
. apt [-h]
## Example 
.sudo apt full-upgrade
.sudo apt install nginx 

# Command name: 
.pwd
## Description
.pwd is used for displaying the current working directory.
## Syntax 
pwd
## Example 
.pwd -P
.pwd -L
.pwd

# Command name: 
cd
## Description
.cd helps the user to change the current working directory to a different directory. 
## Syntax 
.cd + destination
## Example 
.cd /iloveyou
.cd /downloads/cis106

# Command name: 
ls
## Description
.ls is used for listing the content of a given directory or the file/directory itself. 
## Syntax 
.ls 
## Example 
.ls : list the content of the present working directory 
.ls -a: It shows the list and hidden files 
.ls -a ~/Pictures: list all the files inside a given directory 

# Command name: 
tree
## Description
.Tree will list contents of directories in a tree like format. 
## Syntax 
.tree
## Example 
.tree -df
.tree

# Command name: 
man
## Description
.man is the system manual page. Man is look for the help manual. 
## Syntax 
.man [OPTION]... [COMMAN NAME]...
## Example 
.man printf 
.man -f ls
.man -k cd

# Command name: 
mkdir 
## Description
.mkdir is a command that allows the user to make directories 
## Syntax 
.mkdir + directory
## Example 
.mkdir iloveyou
.mkdir {test1, test2,test3}
.mkdir -P {one,two,three}/deva{andalai, maniu,manuki}

# Command name: 
touch 
## Description
.touch is a command that allows the user to create files. 
## Syntax 
.touch <math, science, art>
## Example 
touch math science art 

# Command name: 
rm
## Description
.rm is a command that allows you to remove object such as files, directories from the file system like UNIX. 
## Syntax 
.rm [OPTION]... [FILE]
## Example 
.rm -r*
.rm -i d.txt

# Command name: 
cp 
## Description
.copy source to destination, or multiple sources to directory. 
## Syntax 
.cp [OPTION]
## Example 
cp -i a.txt b.txt

# Command name: 
mv
## Description
.This command moves from one destination from another destination.
## Syntax 
.mv [OPTION]...SOURCE..DIRECTORY
## Example 
.mv sample1.txt sample2.txt sample3.txt ~/Documents/

# Command name: 
stat
## Description
. It shows the file system status. 
## Syntax 
.mv [OPTION]..FILE
## Example 
.stat /etc/

# Command name: 
wildcards 
## Description
.wilcards are symbols or speacial character, you can use them with any command such as ls or rm command to list or remove files. 
## Syntax 
.+ option or option *
## Example 
.mv docs* markdown* pdfs*

# Command name: 
mv
## Description
.This command moves from one destination from another destination.
## Syntax 
.mv [OPTION]...SOURCE..DIRECTORY
## Example 
.mv sample1.txt sample2.txt sample3.txt ~/Documents/

# Command name: 
Brace expansion
## Description
.Brace expansion is a mechanism by which arbitrary string may be generated. 
## Syntax 
.{}
## Example 
.echo {one,two, three, four}

# Command name: 
cat
## Description
The cat command is used for displaying the content of a file. 
## Syntax 
cat + option + file(s) to display 
## Example 
Display the content of a file located in the pwd 
    . cat todo.md 
Display the content of a file using absolute path 
    . cat ~/Documents/todo.md
Display the content of file with line numbers
    . cat -n ~/Documents/todo.md 

# Command name: 
head
## Description: 
The head command displays the top N number of lines of a given file. By defaults, it prints the first 10 lines. 
## Syntax: 
head + option + file(s)
## Example: 
Display the last 10 lines of a file 
    tail ~/Documents/Book/dracula.txt 

# Command name: 
tail
## Description: 
Output the last par of file  
## Syntax: 
tail [option]
## Example: 
tail  +25 bible.txt 

# Command name: 
gzip
## Description: 
.The gzip command reduces the size. 
## Syntax: 
.gzip [file]
## Example: 
gzip -k cereal.csv

# Command name: 
.cut
## Description: 
.remove sections from each line of files 
## Syntax: 
cut [OPTION]
## Example: 
cut -b 1,2,3 file.csv 

# Command name: 
tar
## Description: 
tar _A [OPTIONS] 
## Syntax: 
tar -A [OPTIONs] ARCHIVE
## Example: 
tar cvf file.tar *.c

# Command name: 
chmod
## Description: 
.chmod changes the file mode bits of each given file. 
## Syntax: 
.chmod[option]
## Example: 
chmod u=rw,og=r peru.txt 