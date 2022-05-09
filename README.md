# wsl-commands

<a name="table-of-contents"></a>
## Table of Contents

- [Shortcuts](#shortcuts)
- [Terminal](#terminal)
- [Folder commands](#folder-commands)  
- [File commands](#file-commands)
- [Configure workspace](#ssh-wsl)
    - [Configure SSH Keys](#ssh-wsl) 

<a name="shortcuts"></a>
## Shortcuts
* Kill program execution
<br><code><i>ctrl + c</i></code>
* Clean terminal
<br><code><i>ctrl + l</i></code>
* Autofill
<br><code><i>Tab</i></code>
* Run in the background
<br><code><i>ctrl + z</i></code>
* Exit
<br><code><i>ctrl + d</i></code>
* Move the cursor to the beginning of the line
<br><code><i>ctrl + a</i></code>
* Move the cursor to the end of the line
<br><code><i>ctrl + e</i></code>
* Clean from current position to the beginning
<br><code><i>ctrl + u</i></code>
* Clean entire current line
<br><code><i>ctrl + k</i></code>
* Clean current word
<br><code><i>ctrl + w</i></code>
* Paste deleted code
<br><code><i>ctrl + y</i></code>
* See last command
<br><code><i>ctrl + p</i></code>
* See neat historic command
<br><code><i>ctrl + p</i></code>

[Back to top](#file-commands) 


<a name="terminal"></a>
## Terminal
* Get the current working directory
<br><code>pwd</code>
* Go to new directory
<br><code>cd <i>new\directory</i></code>
* View the contents of a directory
<br><code>ls</code>

[Back to top](#file-commands) 

<a name="folder-commands"></a>
## Folder Commands
* New folder
<br><code>mkdir <i>foldername</i></code>
* Delete folder
<br><code>sudo rm -Rf <i>foldername</i></code>
* Copy directory
<br><code>cp -r <i>old/directory/</i>* <i>new/directory/</i></code>

[Back to top](#file-commands) 

<a name="file-commands"></a>
## File Commands
* New folder
<br><code>touch <i>filename</i></code>

<a name="working-spacel"></a>
## Configure working space

<a name="ssh-wsl"></a>
### Configure SSH in WS
* Step-by-Step
<br><code>sudo apt remove openssh-server</code>
<br><code>sudo apt install openssh-server</code>
<br><code>sudo nano /etc/ssh/sshd_config</code>

[Back to top](#file-commands) 