# Commands to do After Fresh Installation.


<img src="https://img.shields.io/badge/MadHatterENV-github-green"> <img src="https://img.shields.io/badge/code by-GodSpeed-orange">

### SYNOPSIS

Here is the list of **commands** i run after a fresh install<br/>
_Client computers_ are using `Debian` or `Ubuntu`,<br/>
_Servers_ use `CentOS`.<br/>
<img src="/markdown_content/icons/spacer_screensplit.jpg"><br/>
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
## Additional Information
--<br/>
**cerebro**<br/>
Search everything, interact with everything. <br/>
(https://linuxhint.com/install-cerebro-search-ubuntu/)<br/>
(https://cerebroapp.com/)<br/>
 
--<br/>
**xdotool**<br/>
Command-line X11 automation tool<br/>
(https://manpages.debian.org/jessie/xdotool/xdotool.1.en.html) <br/>
 
--<br/>
**wmctrl**<br/>
Interact with a EWMH/NetWM compatible X Window Manager. <br/>
(https://manpages.debian.org/buster/wmctrl/wmctrl.1.en.html) <br/>
 
--<br/>
**Launchy**<br/>
Smart search launcher utility<br/>
(https://manpages.debian.org/buster/launchy/launchy.1.en.html) <br/>
 
--<br/>
**Gigolo**<br/>
A Simple frontend to easily connect to remote filesystems with GIO/GVfs<br/>
(https://manpages.debian.org/buster/gigolo/gigolo.1.en.html) <br/>
 
--<br/>
**Netstat**<br/>
Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships<br/>
(https://manpages.debian.org/buster/net-tools/netstat.8.en.html) <br/>
 
--<br/>
**Htop**<br/>
Interactive Process Viewer<br/>
(https://manpages.debian.org/buster/htop/htop.1.en.html) <br/>
 
--<br/>
**Git**<br/>
Is a fast, scalable, distributed revision control system<br/>
(https://manpages.debian.org/buster/git-man/git.1.en.html) <br/>
 
--<br/>
**Tree**<br/>
List contents of direcotries in a tree-like format<br/>
(https://manpages.debian.org/buster/tree/tree.1.en.html) <br/>
 
--<br/>
**Flameshot**<br/>
Powerfull yet simple-to-use screenshot software<br/>
(https://manpages.debian.org/buster/flameshot/flameshot.1.en.html) <br/>
 
--<br/>
**Kazam**<br/>
Screen recording and capturing program<br/>
(https://manpages.debian.org/buster/kazam/kazam.1.en.html) <br/>
 
--<br/>
**FileZilla**<br/>
Powerfull client for plain FTP, FTP over SSL/TLS (FTPS) and the SSH File Transfer Protocol (SFTP) <br/>
(https://manpages.debian.org/buster/filezilla/filezilla.1.en.html) <br/>
 
--<br/>
**Bacula**<br/>
Network backup solution<br/>
(https://manpages.debian.org/buster/bacula-common/bacula.8.en.html) <br/>
 
--<br/>
**Remmina**<br/>
The GTK+ Remote Desktop Client<br/>
(https://manpages.debian.org/buster/remmina/remmina.1.en.html) <br/>
 
--<br/>
**Okular**<br/>
A Universal document viewer<br/>
(https://manpages.debian.org/buster/okular/okular.1.en.html) <br/>
 
--<br/>
**Audacious**<br/>
An Advanced Audio Player<br/>
(https://manpages.debian.org/buster/audacious/audacious.1.en.html) <br/>
 
--<br/>
**Vagrant**<br/>
Tool for building and distributing virtualized development environments. <br/>
(https://manpages.debian.org/buster/vagrant/vagrant.1.en.html) <br/>
 
--<br/>
**Irssi**<br/>
A modular irc client for unix<br/>
(https://manpages.debian.org/buster/irssi/irssi.1.en.html) <br/>
 
--<br/>
**Sshpass**<br/>
Noninteractive ssh password provider<br/>
(https://manpages.debian.org/buster/sshpass/sshpass.1.en.html) <br/>
 
--<br/>
**Apt-transport-https**<br/>
APT transport for downloading via the (HTTP Secure protocols ((https) <br/>
(https://manpages.debian.org/buster/apt/apt-transport-(https.1.en.html) <br/>
 
--<br/>
**Ansible**<br/>
Define and run a single task 'playbook' against a set of hosts<br/>
(https://manpages.debian.org/buster/ansible/ansible.1.en.html) <br/>
 
--<br/>
**Puppet**<br/>
A more advanced installation/configuration task to a set of hosts<br/>
(https://manpages.debian.org/buster/puppet/puppet.8.en.html) <br/>
 
--
**Gparted**<br/>
Gnome partition editor for manipulating disk partitions<br/>
(https://manpages.debian.org/buster/gparted/gparted.8.en.html) <br/>
 
--<br/>
**Python3-pip**<br/>
A tool for installing and managing Python packages<br/>
(https://manpages.debian.org/buster/python-pip/pip.1.en.html) <br/>
 
--<br/>
**Netdiscover**<br/>
Active/passive ARP reconnaissance tool<br/>
(https://manpages.debian.org/buster/netdiscover/netdiscover.8.en.html) <br/>
 
--<br/>
**Hydra**<br/>
A very fast network logon cracker<br/>
(https://manpages.debian.org/buster/hydra/hydra.1.en.html) <br/>
 
--<br/>
**Burp Security Suite**<br/>
Web vulnerability scanner<br/>
(https://portswigger.net/burp)<br/>
 
--<br/>
**Pv**<br/>
Monitor the progress of data through a pipe<br/>
(https://manpages.debian.org/buster/pv/pv.1.en.html) <br/>
 
--<br/>
**Awk**<br/>
Pattern-directed scanning and processing language<br/>
(https://manpages.debian.org/buster/9base/awk.1plan9.en.html) <br/>
 
--<br/>
**Gzip**<br/>
Gzip, gunzip, zcat - compress or expand files<br/>
(https://manpages.debian.org/buster/gzip/gzip.1.en.html) <br/>
 
--<br/>
**Ack**<br/>
Grep-like tekst finder<br/>
(https://manpages.debian.org/buster/ack/ack.1p.en.html) <br/>
 
--<br/>
**Mtr**<br/>
A network diagnostic tool<br/>
(https://manpages.debian.org/buster/mtr/mtr.8.en.html) <br/>
 
--<br/>
**Pydf**<br/>
Report colourised filesystem disk space usage<br/>
(https://manpages.debian.org/buster/pydf/pydf.1.en.html) <br/>
 
--<br/>
**Lftp**<br/>
Sophisticated file transfer program<br/>
(https://manpages.debian.org/buster/lftp/lftp.1.en.html) <br/>
 
--<br/>
**Nnn**<br/>
The missing terminal file manager for X<br/>
(https://manpages.debian.org/buster/nnn/nnn.1.en.html) <br/>
 
--<br/>
**Xclip**<br/>
Command line interface to X selections (clipboard) <br/>
(https://manpages.debian.org/buster/xclip/xclip.1.en.html) <br/>
 
--<br/>
**Ncdu**<br/>
Ncurses Disk Usage<br/>
(https://manpages.debian.org/buster/ncdu/ncdu.1.en.html) <br/>
 
--<br/>
**Lolcat**<br/>
Filters for textbases figlets adjustments<br/>
(https://manpages.debian.org/buster/filters/LOLCAT.6.en.html) <br/>
 
--<br/>
**Figlet**<br/>
Display large characters made up of ordinary screen characters<br/>
(https://manpages.debian.org/testing/figlet/figlet.6.en.html) <br/>

--<br/>
**Toilet**<br/>
Display large colourful characters<br/>
(https://manpages.debian.org/testing/toilet/toilet.1.en.html) <br/>

--<br/>
**Chafa**<br/>
Character art facsimile generator<br/>
(https://manpages.debian.org/testing/chafa/chafa.1.en.html) <br/>
 
--<br/>
**Dstat**<br/>
Versatile tool for generating system resource statistics<br/>
(https://manpages.debian.org/testing/dstat/dstat.1.en.html) <br/>
 
--<br/>
**Sar**<br/>
Collect, report or save system activity information<br/>
(https://manpages.debian.org/testing/sysstat/sar.1.en.html) <br/>
 
--<br/>
**Glances**<br/>
A ncursed-based monitoring tool<br/>
(https://manpages.debian.org/testing/glances/glances.1.en.html) <br/>
 
--<br/>
**Slurm**<br/>
Network Load Monitor<br/>
(https://manpages.debian.org/testing/slurm/slurm.1.en.html) <br/>
 
--<br/>
**Ttyrec**<br/>
A TTY Recorder<br/>
(https://manpages.debian.org/testing/ttyrec/ttyrec.1.en.html) <br/>
 
--<br/>
**Ipbt**<br/>
Play back tty recording files with random access<br/>
(https://manpages.debian.org/testing/its-playback-time/ipbt.1.en.html) <br/>
 
--<br/>
**Multitail**<br/>
Browse through several files at once ( logs ) <br/>
(https://manpages.debian.org/testing/multitail/multitail.1.en.html) <br/>
 
--<br/>
**Socat**<br/>
Multipurpose relay ( Sockets ) <br/>
(https://manpages.debian.org/testing/socat/socat.1.en.html) <br/>
 
--<br/>
**Netpipes**<br/>
A package to manipulate BSD TCP/IP stream sockets<br/>
(https://manpages.debian.org/testing/netpipes/netpipes.1.en.html) <br/>
 
--<br/>
**Tpp**<br/>
Tekst presentation program<br/>
(https://manpages.debian.org/testing/tpp/tpp.1.en.html) <br/>
 
--<br/>
**Iftop**<br/>
Display bandwidth usage on an interface by host<br/>
(https://manpages.debian.org/testing/iftop/iftop.8.en.html) <br/>
 
--<br/>
**Nethogs**<br/>
Net top tool grouping bandwith per process<br/>
(https://manpages.debian.org/testing/nethogs/nethogs.8.en.html) <br/>
 
--<br/>
**Xargs**<br/>
Build and execute command lines from standard input<br/>
(https://manpages.debian.org/testing/findutils/xargs.1.en.html) <br/>
 
--<br/>
**Parallel**<br/>
Runs programs in parallel<br/>
(https://manpages.debian.org/testing/moreutils/parallel.1.en.html) <br/>
 
--<br/>
**Duplicity**<br/>
Encrypted incremental backup to local or remote storage<br/>
(https://manpages.debian.org/testing/duplicity/duplicity.1.en.html) <br/>
 
--<br/>
**Rsyncrypto**<br/>
Rsync friendly encryption<br/>
(https://manpages.debian.org/unstable/rsyncrypto/rsyncrypto.1.en.html) <br/>
 
--<br/>
**Ledger**<br/>
Command-line, double-entry account reporting tool<br/>
(https://manpages.debian.org/unstable/ledger/ledger.1.en.html) <br/>
 
--<br/>
**Remind**<br/>
A sophisticated reminder service<br/>
(https://manpages.debian.org/buster/remind/remind.1.en.html) <br/>
 
--<br/>
**Rsstail**<br/>
A console based RSS news reader<br/>
(https://manpages.debian.org/buster/rsstail/rsstail.1.en.html) <br/>
 
--<br/>
**Cloc**<br/>
Count or compute differences of lines of source code and comments<br/>
(https://manpages.debian.org/buster/cloc/cloc.1.en.html) <br/>
 
--<br/>
**Qalc**<br/>
Powerful and easy to use command-line calculator<br/>
(https://manpages.debian.org/buster/qalc/qalc.1.en.html) <br/>
 
--<br/>
**Ipcalc**<br/>
An ipv4 netmask/broadcast.. Calculator<br/>
(https://manpages.debian.org/buster/ipcalc/ipcalc.1.en.html) <br/>
 
--<br/>
**Hexyl**<br/>
A command-line hex viewer<br/>
(https://manpages.debian.org/buster/hexyl/hexyl.1.en.html) <br/>
 
--<br/>
**Jq**<br/>
Command-line JSON Processor<br/>
(https://manpages.debian.org/buster/jq/jq.1.en.html) <br/>
 
--<br/>
**Inxi**<br/>
Command-line system information script for console and irc<br/>
(https://manpages.debian.org/buster/inxi/inxi.1.en.html) <br/>
 
--<br/>
**s-tui**<br/>
Curses-based cpu monitoring<br/>
(https://manpages.debian.org/buster/s-tui/s-tui.1.en.html) <br/>
 
--<br/>
**Most**<br/>
Browse or page through a tekst file<br/>
(https://manpages.debian.org/buster/most/most.1.en.html) <br/>
 
--<br/>
**Borg**<br/>
Deduplicating and encrypting backup tool<br/>
(https://manpages.debian.org/buster/borgbackup/borg.1.en.html) <br/>
 
--<br/>
**Ddgr**<br/>
DuckDuck gro from the terminal<br/>
(https://manpages.debian.org/buster/ddgr/ddgr.1.en.html) <br/>
 
--<br/>
**Lnav**<br/>
Ncurses-based log file viewer<br/>
(https://manpages.debian.org/buster/lnav/lnav.1.en.html) <br/>
 
--<br/>
**W3m**<br/>
A tekst based web-browser and pager<br/>
(https://manpages.debian.org/buster/w3m/w3m.1.en.html) <br/>
 
--<br/>
**Buku**<br/>
Bookmark manager like a tekst-based mini-web<br/>
(https://manpages.debian.org/buster/buku/buku.1.en.html) <br/>
 
--<br/>
**Hub**<br/>
Make git easier with github<br/>
(https://manpages.debian.org/buster/hub/hub.1.en.html) <br/>
 
--<br/>
**Pdftk**<br/>
A handy tool for manipulating PDF<br/>
(https://manpages.debian.org/testing/pdftk-java/pdftk.1.en.html) <br/>
 
--<br/>
**Watch**<br/>
Execute a program periodically, showing output fullscreen<br/>
(https://manpages.debian.org/testing/procps/watch.1.en.html) <br/>
 
--<br/>
**Unp**<br/>
A shell frontend for uncompressing/unpacking tools<br/>
(https://manpages.debian.org/buster/unp/unp.1.en.html) <br/>
 
--<br/>
**Espeak**<br/>
A multi-langual software speech synthesizer<br/>
(https://manpages.debian.org/buster/espeak-ng-espeak/espeak.1.en.html) <br/>
 
--<br/>
**Ccze**<br/>
A robust log colorizer<br/>
(https://manpages.debian.org/buster/ccze/ccze.1.en.html) <br/>
 
--<br/>
**Column**<br/>
Utility to format output into multple columns<br/>
(https://manpages.debian.org/buster/bsdmainutils/column.1.en.html) <br/>
 
--<br/>
**Axel**<br/>
Light command-line download accelerator<br/>
(https://manpages.debian.org/buster/axel/axel.1.en.html) <br/>
 
--<br/>
**Finch**<br/>
A console-based frontend to libpurple ( a IM client ) <br/>
(https://manpages.debian.org/buster/finch/finch.1.en.html) <br/>
 
--<br/>
**Rtv**<br/>
Reddit terminal viewer<br/>
(https://manpages.debian.org/buster/rtv/rtv.1.en.html) <br/>
 
--<br/>
**Autojump**<br/>
A faster way to navigate your filesystem<br/>
(https://manpages.debian.org/buster/autojump/autojump.1.en.html) <br/>
 
--<br/>
**Namei**<br/>
Follow a pathname until a terminal point is found<br/>
(https://manpages.debian.org/buster/util-linux/namei.1.en.html) <br/>
 
--<br/>
**Sshuttle**<br/>
Allows you to create a vpn connection<br/>
(https://manpages.debian.org/buster/sshuttle/sshuttle.1.en.html) <br/>
 
--<br/>
**Lynx**<br/>
A general purpose distribute information browser<br/>
(https://manpages.debian.org/buster/lynx-common/lynx.1.en.html) <br/>
 
--<br/>
**Pwgen**<br/>
Generates pronounceable passwords<br/>
(https://manpages.debian.org/buster/pwgen/pwgen.1.en.html) <br/>
 
--<br/>
**Forkstat**<br/>
A tool to show process fork/exec/exit activity<br/>
(https://manpages.debian.org/buster/forkstat/forkstat.8.en.html) <br/>
 
--<br/>
**Ccat**<br/>
Encrypt and recrypt files and streams<br/>
(https://manpages.debian.org/buster/ccrypt/ccat.1.en.html) <br/>
 
--<br/>
**Ts**<br/>
Timestamp input<br/>
(https://manpages.debian.org/buster/moreutils/ts.1.en.html) <br/>
 
--<br/>
<img src="/markdown_content/icons/checklist.jpg"><br/>

## Extra's
- [Web-Dev Tools](https://stackify.com/top-command-line-tools/).
- [AwesomeList](https://github.com/agarrharr/awesome-cli-apps).
- [Network Monitoring Tools](https://haydenjames.io/linux-networking-commands-scripts/).

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

