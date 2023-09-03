# Basic Linux commands
```  ls: ``` Lists all files and directories in the present working directory.  
```  ls -R: ```  Lists files in sub-directories as well.  
```  ls -a: ```  Lists hidden files as well.  
```  ls -al: ```  Lists files and directories with detailed information like permissions, size, owner, etc.  
```  cd or cd ~: ```  Navigates to the HOME directory.  
```  cd ..:  ``` Moves one level up in the directory structure.  
```  cd:  ``` Changes to a particular directory.  
```  cd /:  ``` Moves to the root directory.  
```  cat > filename:  ``` Creates a new file.  
```  cat filename:  ``` Displays the content of a file.  
```  cat file1 file2 > file3:  ``` Joins two files (file1 and file2) and stores the output in a new file (file3).  
```  mv file "new file path":  ``` Moves the file to a new location.  
```  mv filename new_file_name:  ``` Renames the file to a new filename.  
```  sudo:  ``` Allows regular users to run programs with the security privileges of the superuser or root.  
```  rm filename: ```  Deletes a file.  
```  man:  ``` Provides help information on a command.  
```  history: ```  Lists all past commands typed in the current terminal session.  
```  clear:  ``` Clears the terminal.  
```  mkdir directoryname:  ``` Creates a new directory in the present working directory or at the specified path.  
```  rmdir:  ``` Deletes an empty directory.  
# File Permission Commands:

```  ls -l:   ``` Shows file type and access permissions.  
```  r:   ``` Represents read permission.  
```  w:   ``` Represents write permission.  
```  x:  ```  Represents execute permission.  
```  -:   ``` Indicates no permission.  
```  chown user:   ``` Changes the ownership of a file or directory.  
```  chown user:group filename:   ``` Changes both the user and group for a file or directory.  
# Environment Variables Commands:

```  echo $VARIABLE:  ```  Displays the value of a variable.  
```  env:   ``` Displays all environment variables.  
```  VARIABLE_NAME= variable_value:   ``` Creates a new variable.  
```  unset:   ``` Removes a variable.  
```  export Variable=value:   ``` Sets the value of an environment variable.  
#   User Management Commands:

```  sudo adduser username:  ```  Adds a new user.  
```  sudo passwd -l 'username':  ```  Changes the password of a user.  
```  sudo userdel -r 'username':  ```  Removes a newly created user.  
```  sudo usermod -a -G GROUPNAME USERNAME:   ``` Adds a user to a group.  
```  sudo deluser USER GROUPNAME:  ```  Removes a user from a group.  
```  finger:  ```  Shows information about all users logged in.  
```  finger username:  ```  Gives information about a particular user.  
# Networking Commands:

```  SSH username@ip-address or hostname:  ```  Logs into a remote Linux machine using SSH.  
```  ping hostname or ping ip-address:  ```  Pings and analyzes network and host connections.  
```  dir:  ```  Displays files in the current directory of a remote computer.  
```  cd "dirname":  ```  Changes the directory to "dirname" on a remote computer.  
```  put file:  ```  Uploads 'file' from the local to the remote computer.  
```  get file:  ```  Downloads 'file' from the remote to the local computer.  
```  quit:  ```  Logs out.  
# Process Commands:

```  bg:  ```  Sends a process to the background.  
```  fg:  ```  Runs a stopped process in the foreground.  
```  top:  ```  Provides details on all active processes.  
```  ps:  ```  Gives the status of processes running for a user.  
```  ps PID:  ```  Provides the status of a particular process.  
```  pidof:  ```  Gives the Process ID (PID) of a process.  
```  kill PID:  ```  Terminates a process.  
```  nice:  ```  Starts a process with a given priority.  
```  renice:  ```  Changes the priority of an already running process.  
```  df:  ```  Provides free hard disk space on your system.  
```  free:  ```  Displays free RAM on your system.  
# VI Editing Commands:

```  i:  ```  Inserts at the cursor (enters insert mode).  
```  a:  ```  Writes after the cursor (enters insert mode).  
```  A:  ```  Writes at the end of the line (enters insert mode).  
```  ESC:  ```  Terminates insert mode.  
```  u:  ```  Undoes the last change.  
```  U:  ```  Undoes all changes to the entire line.  
```  o:  ```  Opens a new line (enters insert mode).  
```  dd:  ```  Deletes a line.  
```  3dd:  ```  Deletes three lines.  
```  D:  ```  Deletes contents of the line after the cursor.  
```  C:  ```  Deletes contents of a line after the cursor and inserts new text. Press the ESC key to end insertion.  
```  dw:  ```  Deletes a word.  
```  4dw:  ```  Deletes four words.  
```  cw:  ```  Changes a word.  
```  x:  ```  Deletes a character at the cursor.  
```  r:  ```  Replaces a character.  
```  R:  ```  Overwrites characters from the cursor onward.  
```  s:  ```  Substitutes one character under the cursor and continues to insert.  
```  S:  ```  Substitutes the entire line and begins to insert at the beginning of the line.  
```  ~:  ```  Changes the case of an individual character.  
###  These commands cover a wide range of Linux operations and should help you navigate and work effectively in a Linux environment.
