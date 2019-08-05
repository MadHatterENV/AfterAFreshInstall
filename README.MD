# Commands to do After Fresh Installation.


<img src="https://img.shields.io/badge/MadHatterENV-github-green"> <img src="https://img.shields.io/badge/code by-GodSpeed-orange">

### SYNOPSIS

Here is the list of **commands** i run after a fresh install
_Client computers_ are using `Debian` or `Ubuntu`,
_Servers_ use `CentOS`.

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


  131  sudo apt install cerebro
  132  sudo apt install xdotool
  133  sudo apt install wmctrl
  139  sudo apt install cherrytree
  475  sudo apt install libzmq5
 1136  sudo apt install software-properties-common
 1243  sudo apt install update

  
# File Explorer
  125  sudo apt install dolphin
 1523  sudo apt install doublecmd-gtk
  603  sudo apt install konsole

# File/Command Finder
  128  sudo apt install launchy
  460  sudo apt install updatedb
  461  sudo apt install locate

# Network Tools #
  135  sudo apt install gigolo
  137  sudo apt install gsshfs
  138  sudo apt install pac
 1651  sudo apt install sshmenu-gnome
 1652  sudo apt install sshmenu
 1653  sudo apt install kitty

# Network Diagnostics
  426  sudo apt install netstat
  427  sudo apt install net-tools

# Process Diagnostics
  577  sudo apt install htop

# Coding #
  253  sudo apt install code
  290  sudo apt install git
  404  sudo apt install tree
 1088  sudo apt install sublime-text

# Screenshot App
  606  sudo apt install flameshot

# Audio Tools
  610  sudo apt install kazam

# File/Transfert App
  611  sudo apt install filezilla

# Backup Tool
  451  sudo apt install syncting
  612  sudo apt install bacula

# Extra Apps
  613  sudo apt install simplenote
  621  sudo apt install uget
  623  sudo apt install thunderbird
  624  sudo apt install keepassxc
  625  sudo apt install remmina
  626  sudo apt install okular
  627  sudo apt install audacious
  628  sudo apt install winds
  629  sudo apt install fontmatrix
  630  sudo apt install fontbase
  631  sudo apt install font-manager

# Install Vagrant
  632  sudo apt install vagrant

# Install IRC Chat
  655  sudo apt install irssi
  656  sudo apt install irssi-scripts

# Install Ansible + Dependecies
  665  sudo apt install sshpass
 1084  sudo apt install apt-transport-https

  678  sudo apt install ansible
  679  sudo apt install puppet

# Partition Manager
  811  sudo apt install gparted

# Python Extra Tools
  826  sudo apt install python3-pip

# Network Security Tools (Hacking)
  835  sudo apt install netdiscover
  842  sudo apt install nikto
  844  sudo apt install burp 
  848  sudo apt install hydra
  853  sudo apt install openjdk-11-jre

# Taking Notes ( OneNote Alternative )
  869  sudo apt install xournal
 1244  sudo apt install rednotebook

# Upgraded CLI commands
 1693  sudo apt install pv
 1694  sudo apt install awk
 1753  sudo apt install gzip
 1923  sudo apt install ack
 1924  sudo apt install silversearcher-ag
 1927  sudo apt install mtr
 1930  sudo apt install pydf
 1933  sudo apt install lftp
 1936  sudo apt install aria2
 1937  sudo apt install nnn
 1940  sudo apt install wikit
 1955  sudo apt install bat
 1978  sudo apt install incron
 1980  sudo apt install xclip
 1985  sudo apt install ncdu
 1988  sudo apt install lolcat
 1989  sudo apt install figlet
 1990  sudo apt install toilet
 1991  sudo apt install chafa
 1992  sudo apt install dstat
 1993  sudo apt install sar
 1994  sudo apt install glances
 1996  sudo apt install slurm
 1997  sudo apt install ttyrec
 1998  sudo apt install ipbt
 1999  sudo apt install multitail
 2000  sudo apt install socat
 2001  sudo apt install netpipes
 2002  sudo apt install tpp
 2003  sudo apt install iftop
 2004  sudo apt install iptraf
 2005  sudo apt install nethogs
 2006  sudo apt install xargs
 2007  sudo apt install parallel
 2008  sudo apt install duplicity
 2009  sudo apt install rsyncrypto
 2012  sudo apt install ledger
 2013  sudo apt install taskwarrior
 2014  sudo apt install pt
 2015  sudo apt install remind
 2016  sudo apt install ttytter
 2017  sudo apt install earthquake
 2018  sudo apt install rsstail
 2019  sudo apt install tig
 2020  sudo apt install cloc
 2021  sudo apt install qcalc
 2022  sudo apt install ipcalc
 2023  sudo apt install calcurse
 2024  sudo apt install colordiff
 2025  sudo apt install qalc
 2026  sudo apt install hexyl
 2027  sudo apt install httpie
 2028  sudo apt install jq
 2029  sudo apt install ripgrep
 2030  sudo apt install json_pp
 2031  sudo apt install inxi
 2033  sudo apt install s-tui
 2035  sudo apt install corefreq
 2036  sudo apt install most
 2037  sudo apt install borg
 2038  sudo apt install tmsu
 2039  sudo apt install pup
 2040  sudo apt install xiki
 2041  sudo apt install ddgr
 2044  sudo apt install lnav
 2045  sudo apt install w3m
 2048  sudo apt install buku
 2049  sudo apt install hub
 2050  sudo apt install pdftk
 2051  sudo apt install socat
 2052  sudo apt install watch
 2053  sudo apt install ytcc
 2055  sudo apt install grv
 2056  sudo apt install cmus
 2057  sudo apt install mpd
 2058  sudo apt install mpc
 2059  sudo apt install ncmpcpp
 2060  sudo apt install unp
 2061  sudo apt install teleport
 2062  sudo apt install espeak
 2065  sudo apt install ccze
 2066  sudo apt install column
 2067  sudo apt install hh
 2068  sudo apt install axel
 2069  sudo apt install finch
 2070  sudo apt install rtv
 2071  sudo apt install autojump
 2073  sudo apt install namei
 2074  sudo apt install sshuttle
 2075  sudo apt install cheat
 2076  sudo apt install lynx
 2077  sudo apt install pwgen
 2078  sudo apt install tig
 2079  sudo apt install convert
 2081  sudo apt install forkstat
 2082  sudo apt install bashmarks
 2083  sudo apt install ccat
 2084  sudo apt install netdiscover
 2085  sudo apt install fdclone
 2087  sudo apt install ts
 2101  sudo apt install libart
 2102  sudo apt install libart-2.0.2
 2107  history | grep sudo apt install > software_installations.txt


```









## Coded with
- All my code are coded/debugged with [VS Code](https://code.visualstudio.com/).

## Versioning
:octocat: We use [SemVer](http://semver.org/) for versioning. 


## Author(s)
This script was only written by :zap: [GodSpeed](--GodSpeed--) :zap:

## License
This project/code/script is licensed under the :copyright: [MIT license](mit)


## Acknowledgement
- Hat tip to the guys and girls who maintain the `man date` :)
- Badges generated with [shields.io](https://shields.io)
- Emojo [Cheatsheet](https://www.webfx.com/tools/emoji-cheat-sheet/) | [cheatlist](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
- Markdown [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) | Github [Mastering](https://guides.github.com/features/mastering-markdown/)
- [Markdown Guide](https://about.gitlab.com/handbook/product/technical-writing/markdown-guide/)
- [Code Sandbox](https://codesandbox.io/)

