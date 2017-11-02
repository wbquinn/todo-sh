# todo-sh
Simple note capture scripts - handy for todos

Provides a set of scripts to add, list and edit a todo file, and 
aliases to quickly call them from a shell/console/terminal session.


## Configurable items:

`$TODO_HOME`  the location of the folder where the notes files are created
- defaults to ~/to-do if not set explicitly
  
`$TODO_BIN`  the location of these scripts

`$TODO_FILE_BASE`  root name for the created notes files 
- defaults to "todo-"
  
`$TODO_FILE_DATE_FORMAT`  the date/time format used in the created files 
- defaults to "%F"
  
`$TODO_FILE_EXT`  extension of the notes files created 
- defaults to "todo"


## Installation
 - create a folder to hold these scripts (i.e. `$TODO_BIN`)
 - create a folder for the notes files (i.e. `$TODO_HOME`)
   - I suggest a shared/replicated/backed-up location 
   - like Google Drive, OneDrive, Dropbox, nfs mounted home, etc.
 - update this file with the location information
 - update this file with any customization of the file name
 - update your shell's .profile or .shrc file (e.g. `~/.bash_profile) 
    - add a call to this shell scipt
    - to set the path and aliases in your shells
 - start new shell and type addtd to add your first note...

