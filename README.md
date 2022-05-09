# wsl-commands

<a name="table-of-contents"></a>
## Table of Contents
[Configure SSH in WSL](#ssh-wsl) 
[Folder commands](#folder-commands)  
[File commands](#file-commands)  


<a name="ssh-wsl"></a>
## Configure SSH in WS
* Step-by-Step
<br><code>sudo apt remove openssh-server</code>
<br><code>sudo apt install openssh-server</code>
<br><code>sudo nano /etc/ssh/sshd_config</code>
AllowUsers <your_username>




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
