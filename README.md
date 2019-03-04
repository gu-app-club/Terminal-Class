# Terminal-Fun
Using the terminal in everyday programming life can make life much, much easier. However, there is a slight learning curve for this. Below will be a list of usable commands and how to use them. 

## The Basics
- ls: List all of the contents of a directory 
  - ls -a (a is for all)
- cd: Change the work directory
  - cd home
- touch: Creates a file 
- mkdir: Create a new directory 
  - mkdir ubuntu (create a directory with the name ubuntu) 
- rm: Remove
  - rm max (removes a file with the name Max) 
  - rm max/ -rf (removes all contents of a directory) 
- mv: Moves the contents of a file 
  - mv old_file new_file 
- cp: copy 
  - cp old_file new_file -r (-r) does this recurively for a directory) 
- file: Displays the content of a given file 
  - file hack.sh 
- man: The manual for the Linux OS. Probably more useful than Stack Overflow. Please read docs! 
  - man touch (Gets the manual for the touch command) 

## Good To Knows 
- cat: Shows the contents of a file 
  - cat something.py 
- tail/head: Tail shows the last 10 lines and head shows the first 10. 
  - tail something.py 
- less: Opens the file in a scrollable mode 
- more: Opens the file to only scroll downwards. 
- grep: A string based search tool 
  - grep 'jacob' something.py -r 
- find: Used for filename searches 
  - find -name 'something.py' . 
- echo: Displays the text given 
  - echo 'kevin' 
- ps: Checks for processs information 
- sudo/su: Log in as the superuser 

## Linux Domination 
- ; 
  - Used for chaining commands together 
  - ls; ps; 
- &
  - Running a process in the background 
  - python something.py &
- !! 
  - Will run the previous command 
  - sudo !! 
- Tab completition: 
  - Press tab while typing a command for autofilling 
- >>
  - Output information into a file 
  - ls >> output.txt 
- | 
  - The grand daddy of them all! 
  - How to chain commands to together!
  - ls | grep '*.sh' (Puts the output of ls into the grep command)
- cut: 
  - Carving information out of previous commands
  - ls | grep 

## Command Line Tools 
- ssh: 
  - Secure Shell (What Putty is) 
  - ssh mdulin2@ada.gonzaga.edu 
- scp: 
  - Secure Copy (How to transfer files) 
  - scp some_file.sh mdulin2@ada.gonzaga.edu:~/some_directory
- curl: 
  - Making web requests
  - Too much to show here...
## Text Editors 
- vim:
  - Different modes of operation (insertion and regular) 
  - Press `i` to go into insert mode. Use ESC to escape it. 
  - k to move up; j to move down; l to move right; h to move left 
  - o to insert at the next line 
  - SHIFT + a to insert at the end of the line 
  - :w to save 
  - :wq to save and quite 
  - :q! to force quite 
  - /some_string to search the file for a string. 
- nano
