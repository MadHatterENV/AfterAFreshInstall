# Commands to do After Fresh Installation.


<img src="https://img.shields.io/badge/MadHatterENV-github-green"> <img src="https://img.shields.io/badge/code by-GodSpeed-orange">

### SYNOPSIS

Here is the list of **commands** i run after a fresh install<br/>
_Client computers_ are using `Debian` or `Ubuntu`,<br/>
_Servers_ use `CentOS`.<br/>

You can do this manually in your bash, or use Ansible to push the commands via a playbook to the designated clients/server-pools.

<img src="/markdown_content/icons/code1.jpg"><br/>

### LATEST REVISION
- Latest adjusted on 04/08/2019.


## Installation & prerequisites
Currently only this README.MD is included
In the future you will be able to clone this repo onto your machine.


Instructions

Just clone this repo or download the `command_installer.sh` script, add the execute permission (`chmod +x command_installer.sh`).

## List Of Commands

```
## Applications in XFCE ##

# Extra Tools
sudo apt install cerebro
sudo apt install xdotool
sudo apt install wmctrl
sudo apt install cherrytree
sudo apt install libzmq5

sudo apt install software-properties-common
sudo apt install update
  
# File Explorer Tools
sudo apt install dolphin
sudo apt install doublecmd-gtk
sudo apt install konsole

# File/Command Finder Tools
sudo apt install launchy
sudo apt install updatedb
sudo apt install locate

# Network/Folder Mounting Tools
sudo apt install gigolo
sudo apt install gsshfs
sudo apt install pac
sudo apt install sshmenu-gnome
sudo apt install sshmenu
sudo apt install kitty

# Network Diagnostics Tools
sudo apt install netstat
sudo apt install net-tools

# Process Diagnostics Tools
sudo apt install htop

# Coding Tools
sudo apt install code
sudo apt install git
sudo apt install tree
sudo apt install sublime-text

# Screenshot Tools
sudo apt install flameshot

# Audio Tools
sudo apt install kazam

# File/Transfert Tools
sudo apt install filezilla

# Backup/Sync Tools
sudo apt install syncting
sudo apt install bacula

# Extra Apps
sudo apt install simplenote
sudo apt install uget
sudo apt install thunderbird
sudo apt install keepassxc
sudo apt install remmina
sudo apt install okular
sudo apt install audacious
sudo apt install winds
sudo apt install fontmatrix
sudo apt install fontbase
sudo apt install font-manager

# Install Vagrant
sudo apt install vagrant

# Install IRC Chat
sudo apt install irssi
sudo apt install irssi-scripts

# Install Ansible + Dependecies
** Prep a list with IP's and DNS names of the machines you wish to control **
sudo apt install sshpass
sudo apt install apt-transport-https

sudo apt install ansible
sudo apt install puppet

# Partition Manager
sudo apt install gparted

# Python Extra Tools
sudo apt install python3-pip

# Network Security Tools (WhiteHat>PenTesting)
sudo apt install netdiscover
sudo apt install nikto
sudo apt install burp 
sudo apt install hydra
sudo apt install openjdk-11-jre

# Taking Notes ( OneNote Alternative )
sudo apt install xournal
sudo apt install rednotebook

# Upgraded CLI commands
sudo apt install pv
sudo apt install awk
sudo apt install gzip
sudo apt install ack
sudo apt install silversearcher-ag
sudo apt install mtr
sudo apt install pydf
sudo apt install lftp
sudo apt install aria2
sudo apt install nnn
sudo apt install wikit
sudo apt install bat
sudo apt install incron
sudo apt install xclip
sudo apt install ncdu
sudo apt install lolcat
sudo apt install figlet
sudo apt install toilet
sudo apt install chafa
sudo apt install dstat
sudo apt install sar
sudo apt install glances
sudo apt install slurm
sudo apt install ttyrec
sudo apt install ipbt
sudo apt install multitail
sudo apt install socat
sudo apt install netpipes
sudo apt install tpp
sudo apt install iftop
sudo apt install iptraf
sudo apt install nethogs
sudo apt install xargs
sudo apt install parallel
sudo apt install duplicity
sudo apt install rsyncrypto
sudo apt install ledger
sudo apt install taskwarrior
sudo apt install pt
sudo apt install remind
sudo apt install ttytter
sudo apt install earthquake
sudo apt install rsstail
sudo apt install tig
sudo apt install cloc
sudo apt install qcalc
sudo apt install ipcalc
sudo apt install calcurse
sudo apt install colordiff
sudo apt install qalc
sudo apt install hexyl
sudo apt install httpie
sudo apt install jq
sudo apt install ripgrep
sudo apt install json_pp
sudo apt install inxi
sudo apt install s-tui
sudo apt install corefreq
sudo apt install most
sudo apt install borg
sudo apt install tmsu
sudo apt install pup
sudo apt install xiki
sudo apt install ddgr
sudo apt install lnav
sudo apt install w3m
sudo apt install buku
sudo apt install hub
sudo apt install pdftk
sudo apt install socat
sudo apt install watch
sudo apt install ytcc
sudo apt install grv
sudo apt install cmus
sudo apt install mpd
sudo apt install mpc
sudo apt install ncmpcpp
sudo apt install unp
sudo apt install teleport
sudo apt install espeak
sudo apt install ccze
sudo apt install column
sudo apt install hh
sudo apt install axel
sudo apt install finch
sudo apt install rtv
sudo apt install autojump
sudo apt install namei
sudo apt install sshuttle
sudo apt install cheat
sudo apt install lynx
sudo apt install pwgen
sudo apt install tig
sudo apt install convert
sudo apt install forkstat
sudo apt install bashmarks
sudo apt install ccat
sudo apt install netdiscover
sudo apt install fdclone
sudo apt install ts
sudo apt install libart
sudo apt install libart-2.0.2

history | grep sudo apt install > software_installations.txt
```


## Coded with
- All my code are coded/debugged with [VS Code](https://code.visualstudio.com/).

## Versioning
:octocat: We use [SemVer](http://semver.org/) for versioning. 

## Author(s)
This script was written by :zap: [GodSpeed](--GodSpeed--) :zap:<br/>
Thanks to the linux-community, this list of applications/commands was compiled during my ICT career.

## License
This project/code/script is licensed under the :copyright: [MIT license](mit)

## Acknowledgement
- Hat tip to the guys and girls who maintain the `man date` :)
- Badges generated with [shields.io](https://shields.io)
- Emojo [Cheatsheet](https://www.webfx.com/tools/emoji-cheat-sheet/) | [cheatlist](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
- Markdown [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) | Github [Mastering](https://guides.github.com/features/mastering-markdown/)
- [Markdown Guide](https://about.gitlab.com/handbook/product/technical-writing/markdown-guide/)
- [Code Sandbox](https://codesandbox.io/)

