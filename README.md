## WSL Ubuntu 20.04
### dotfiles
#### /home/m/ 

* .bashrc  .bash_aliases
* .vimrc   .vimfm
* .tmux.config  makefiles
* .gdb.config
* C small multifile demos
* ~\demoC including gdb
* ~\demoHtml

<pre>
Use cmd or powershell
wsl --list --online
wsl --install -d Ubuntu-22.04

open Ubuntu-22.04
sudo apt update -y
sudo apt upgrade -y
sudo apt autoremove

sudo apt install git -y
sudo apt install gh -y
gh auth login
    GitHub.com
    HTTPS
    y
    Login with a web browser
    copy your one-time code: XXXX-XXXX
 </pre>

* and go to https://github.com/login/device

<pre>
git config --global user.name "Your Name"
git config --global user.email "yourmail@yourdomain.com"
git config list
cat .gitconfig
git config --global init.defaultBranch master
git init

git pull https://github.com/mort1skoda/wslUbuntu2204.git rebase



</pre>

---
* git pull https://github.com/mort1skoda/wslUbuntu2204.git
* git remote -v
---
* ./gitPush.sh   /   alias gp
* cat gitPush.sh to see "how it's done"
* alias c='cat '    c gitPush.sh
* push all the dotfiles in /home/user/
* including the folders:
* .config .landscape .local .vifm .vim
---
* other user data /dat
* Like: 
* devC devHtml devLfs
* they have their own,
* repositories with gitPush.sh
* inside each of their folders
---

<pre>
Filestructure tree:

├── .config
│   ├── htop
│   │   └── htoprc
│   ├── myconf
│   │   └── test.conf
│   └── neofetch
│       └── config.conf
├── .vifm
│   ├── colors
│   │   ├── Default.vifm.bkup
│   │   └── molokai.vifm
│   ├── scripts
│   │   └── README
│   ├── vifm-help.txt
│   ├── vifminfo
│   ├── vifmrc -> vifmrc.vim
│   ├── vifmrc.vim
│   └── vifmrc_BU
├── demo-c
│   ├── 0demo-multifile
│   │   ├── Makefile
│   │   ├── func1.c
│   │   ├── func1.h
│   │   ├── func2.c
│   │   ├── func2.h
│   │   ├── func3.c
│   │   ├── func3.h
│   │   └── main.c
│   └── main.c
├── tutVimScript
│   └── vimScript00preface.txt
├── .bash_aliases
├── .bash_logout
├── .bashrc
├── .gdbinit
├── .gitconfig
├── .gitignore
├── .profile
├── .tmux.conf
├── .vimrc
├── .wget-hsts
├── README.md
├── homeTree.txt
├── info.sh
├── map_caps-lock_esc.txt
├── setupRoot.sh
└── vimPaths.txt
</pre>


