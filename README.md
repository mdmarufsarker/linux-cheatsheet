# linux-cheatsheet

A Beginners guide for Linux users

[Bash Related Commands](##bash-related-commands)

[File / Directory Related Commands](##file--directory-related-commands)

## Bash Related Commands

- Clear the terminal

  clear / ctrl + l

- Close the terminal

  exit / ctrl + d

- Reset the terminal

  reset

- Stop any program

  ctrl + c

- Sleep any program

  ctrl + z

- Check the history

  ctrl + r / history

- Check last 30 commands

  history | tail -30

- Autocomplete Filename or Folder name

  Tab

- Autocomplete command

  Tab twice

- Autocomplete command with options

  Tab three times

## File / Directory Related Commands

- Create a new directory

  mkdir directory-name

- Create a new file

  touch file-name

- Create multiple directories at a time

  - mkdir dir1 dir2 dir3 dir4 dir5

- Create multiple files at a time

  - touch index.html style.css script.js

- Delete a directory with all it's child

  - rm -rf directory-name

- Delete a file

  - rm filename

- List down all the files and directories

  - ls

- List down all the files and directories with all the details

  - ls -l

- List down all the files and directories with all the details and hidden files

  - ls -la

- List down all the files and directories with all the details and hidden files and sort by size

  - ls -lS

- List down all the files and directories with all the details and hidden files and sort by time

  - ls -lt

- List down all the files and directories with all the details and hidden files and sort by time and reverse

  - ls -ltr

- List down all the files and directories with all the details and hidden files and sort by time and reverse and show only 10 files

  - ls -ltr | head -10

- Open a file

  - cat filename

- Open a file with line numbers

  - cat -n filename

- Open a file with line numbers and show only 10 lines

  - cat -n filename | head -10

- Open a file using vim

  - vim filename

- Open a file using vim and show only 10 lines

  - vim +10 filename

- Open a file using nano

  - nano filename

- Open a file using nano and show only 10 lines

  - nano +10 filename

- Open a file using gedit

  - gedit filename

- Count the number of lines in a file

  - wc -l filename

- Print the current working directory

  - pwd

- Change the current working directory

  - cd directory-name

- Change the current working directory to the home directory

  - cd ~

- Change the current working directory to the parent directory

  - cd ..

- Change the current working directory to the root directory

  - cd /

- Copy a file

  - cp filename newfilename

- Copy a file to a directory

  - cp filename directory-name

- Copy a directory

  - cp -r directory-name newdirectory-name

- Copy a directory to a directory

  - cp -r directory-name directory-name

- Move a file

  - mv filename newfilename

- Move a file to a directory

  - mv filename directory-name

- Move a directory

  - mv -r directory-name newdirectory-name

- Move a directory to a directory

  - mv -r directory-name directory-name

- Rename a file

  - mv filename newfilename

- Rename a directory

  - mv directory-name newdirectory-name

- Create a symbolic link

  - ln -s filename linkname

- Create a hard link

  - ln filename linkname

- Create a hard link to a directory

  - ln -r directory-name linkname

- Create a symbolic link to a directory

  - ln -sr directory-name linkname

- Create a file with content

  - echo "Hello World" > filename

- Append content to a file

  - echo "Hello World" >> filename

- Create a file with content and open it using vim

  - echo "Hello World" > filename && vim filename

- Create a file with content and open it using nano

  - echo "Hello World" > filename && nano filename

- Create a file with content and open it using gedit

  - echo "Hello World" > filename && gedit filename

- Create a file with content and open it using cat

  - echo "Hello World" > filename && cat filename
