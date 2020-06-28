
# Git Basic Commands
- $git --version   - Tells current version installed on your desktop
- $git status - Tells if any commits or any recent changes
- $code filename.md - Creates a file on your default code editor
- $git init - Will initialize current directory as default git directory
- $git config --global user.name Balaji Baskaran  - To setup Default user on your system
- $git config --global user.email balaji.b84@gmail.com - To setup Default email on your system
- $git add filname.md -- Add commands tracks the changes so it can be committed. Adding commit before add will do no commit
- $git commit -m "message" - lets you commit you work. -m can help you add message/comment to your commit
- $git commit -am -- am switch is to say you want to track changes to the modified file as well as to write message/comments to your git commit before adding add, the modifed file was in red color stating it wasn't tracked. after adding add or add. it changed to green stating it's being tracked
- $git add. -- lets you track all the files that are in the directory, rather than having to type git -add "eachfilename.md"
- $git config --edit --global - opens the global file using your default editor
- $git log - shows all the commit logs
- $git branch newbranch - Creates a new localbranch but won't switch to the branch directory
- $git checkout newbranch - Will switch to directory
- $git checkout -b newbranch - Do both in same command, create as well as switch to branch
- $git push -u origin newbranch - Will push the changes to branch instead of master
<<<<<<< HEAD
## Creating SSH Key examples
- Add the pub key to the settings in github website. 
- $ ssh-keygen -t rsa -b 4096 -C "balaji.b84@gmail.com"
- Generating public/private rsa key pair.
- Enter file in which to save the key (/c/Users/Balaji/.ssh/id_rsa): balajicomputer
- Enter passphrase (empty for no passphrase):
- Enter same passphrase again:
- Your identification has been saved in balajicomputer
- Your public key has been saved in balajicomputer.pub
- The key fingerprint is:
- SHA256:cxxxxxxxxx balaji.b84@gmail.com
- The key's randomart image is:
- +---[RSA 4096]----+
- |      .    o.+o=+|
- |     =    ..Ooo.=|
- |    * o o .*oo+ =|
- |   . = + ....+o++|
- |    . . S   oo.=*|
- |            oo.++|
- |           ... +.|
- |            . . E|
- |               ..|
- +----[SHA256]-----+
- ssh -T git@github.com - To authenticate automatically using the ssh key

