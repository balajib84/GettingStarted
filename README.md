<<<<<<< HEAD
#Basic Gitcommands
=======
# GitHub commands
This is has list of basic git commands
>>>>>>> 790388cd2700181563e87b56434caa9f4e47ea4c
$git --version   - gets current version installed on your desktop
$git status - Tells if any commits or any recent changes
$code filename.md - creates a file on your default code editor
$git init - will initialize current directory as default git directory
$git config --global user.name Balaji Baskaran
$git config --global user.email balaji.b84@gmail.com
$git add filname.md -- tracks the changes so it can be committed. Adding commit before add will do no commit
$git commit -m "message" - lets you commit you work. -m can help you add message/comment to your commit
$git commit -am -- am switch is to say you want to track changes to the modified file as well as to write message/comments to your git commit
before adding add, the modifed file was in red color stating it wasn't tracked. after adding add or add. it changed to green stating it's being tracked
$git add. -- lets you track all the files that are in the directory, rather than having to type git -add "eachfilename.md"
$git config --edit --global - opens the global file using your default editor
$git log - shows all the commit logs
<<<<<<< HEAD
## Creating SSH Key examples
=======
## creating SSH Key
>>>>>>> 790388cd2700181563e87b56434caa9f4e47ea4c
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Balaji/.ssh/id_rsa): balajigithub
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in balajigithub
Your public key has been saved in balajigithub.pub
The key fingerprint is:
SHA256:rzENtiLlVTWWFcjBm5mN1nl9RlVyEMBCEJRqn/no724 Balaji@Balaji
The key's randomart image is:
+---[RSA 3072]----+
|       .+=.+***+*|
|        . .o*. o.|
|       .  .. O o.|
|      o  .  B + =|
|     ...So .   o.|
|     o o+=       |
|    . o +oo      |
|     . ..+E      |
|       .o=+      |
+----[SHA256]-----+
# add the pub key to the settings in github website. 

$ ssh-keygen -t rsa -b 4096 -C "balaji.b84@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Balaji/.ssh/id_rsa): balajicomputer
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in balajicomputer
Your public key has been saved in balajicomputer.pub
The key fingerprint is:
SHA256:gFMu6fFl9xt9ZH01NIViaVqNeORzSf5PiS5FfzbpY3s balaji.b84@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|      .    o.+o=+|
|     =    ..Ooo.=|
|    * o o .*oo+ =|
|   . = + ....+o++|
|    . . S   oo.=*|
|            oo.++|
|           ... +.|
|            . . E|
|               ..|
+----[SHA256]-----+

# use 'ssh -t git@github.com' to authenticate automatically using the ssh key

