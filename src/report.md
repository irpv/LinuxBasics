# Report


## Part 1
- ![part1](./images/part1.png)
  > cat /etc/issue print current version of your linux based os, in this example - `Ubuntu 20.04.5 LTS`


## Part 2
- ![part2.1](./images/part2-1.png)
  > you can create a user with this command - `adduser [USER_NAME}`

<br>

- ![part2.2](./images/part2-2.png)
  > you can view all users with this command - `cat /etc/passwd`

## Part 3
- ![part3.1](./images/part3-1.png)
  > you can change machine name by editing `/etc/hostname` and `/etc/hosts`

<br>

- ![part3.2](./images/part3-2.png)
  > you can set the timezone with this command `sudo timedatectl set-timezone [YOUR_TIMEZONE]`

<br>

- ![part3.3](./images/part3-3.png)
  > you can view names of the network interfaces with this command - `ip link show` 

  The loopback device (lo) is a special, virtual network interface that your computer uses to communicate with itself. It is used mainly for diagnostics and troubleshooting, and to connect to servers running on the local machine

<br>

- ![part3.4](./images/part3-4.png)
  > you can get the ip fro, the dchp with this command - `sudo dhclinet -v` 

  DHCP stands for Dynamic Host Configuration Protocol 

<br>

- ![part3.5](./images/part3-5.png)
  > you can check your external and internal ip with this commands - `hostname -I` , `curl checkip.amazonaws.com`

<br>

- ![part3.6.1](./images/part3-6-1.png)
  > you can set static ip, gw and dns by editing `/etc/netplan/01-network-manager-all.yaml`

<br>

- ![part3.6.2](./images/part3-6-2.png)
  > you can ping with this command - `ping [REMOTE_HOST]`

## Part 4
- ![part4](./images/part4.png)
  > you can update your ubuntu with this commands - `sudo apt update && sudo apt upgrade`

## Part 5
- ![part5](./images/part5.png)

  sudo allows a system administrator to delegate authority to give certain users—or groups of users—the ability to run commands as root or another user while providing an audit trail of the commands and their arguments. 

## Part 6
- ![part6](./images/part6.png)
  > you can check current time with this command - `date` and current timezone with this command - `timedatectl show`

## Part 7
- ![part7-1-emacs](./images/part7-1-emacs.png)

  you can exit with changes from emacs with this command - `C-x C-s`

<br>

- ![part7-1-nano](./images/part7-1-nano.png)

  you can exit with changes from nano with this command - `^O ^X`

<br>

- ![part7-1-vim](./images/part7-1-vim.png)

  you can exit with changes from vim with this command - `:wq`

<br>

- ![part7-2-emacs](./images/part7-2-emacs.png)

  you can exit with without changes from emacs with this command - `C-x C-c`

<br>

- ![part7-2-nano](./images/part7-2-nano.png)

  you can exit with without changes from nano with this command - `^X`

<br>

- ![part7-2-vim](./images/part7-2-vim.png)

  you can exit with without changes from vim with this command - `:q!`

<br>

- ![part7-3-emacs-1](./images/part7-3-emacs-1.png)

<br>

- ![part7-3-nano-1](./images/part7-3-nano-1.png)

<br>

- ![part7-3-vim-1](./images/part7-3-vim-1.png)

<br>

- ![part7-3-emacs-2](./images/part7-3-emacs-2.png)

<br>

- ![part7-3-nano-2](./images/part7-3-nano-2.png)

<br>

- ![part7-3-vim-2](./images/part7-3-vim-2.png)

## Part 8
- ![part8-1](./images/part8-1.png)
  > `ps` displays information about a selection of the active processes, `-e` flag displays every process on the system 

<br>

- ![part8-2](./images/part8-2.png)
  
  you can install SSHd with `sudo apt install openssh-server` \
  add service to an auto-start with `sudo systemctl enable ssh` \
  reset SSHd to port 2022 by editing `/etc/ssh/sshd_config` \
  reboot system with `reboot`

## Part 9

- ![part9-top](./images/part9(txt).png)

  uptime is 10 min\
  number of authorised users is 1\
  total system load is 0.64%\
  total number of processes is 134\
  cpu load is 5.9%\
  memory load is 695.5\
  pid of the process with the highest memory usage is 758\
  pid of the process taking the most CPU time is 758

<br>

- ![part-9pid](./images/part9-pid.png)

<br>

- ![part-9cpu](./images/part9-cpu.png)

<br>

- ![part-9mem](./images/part9-mem.png)

<br>

- ![part-9time](./images/part9-time.png)

<br>

- ![part-9filter](./images/part9-filter.png)

<br>

- ![part-9search](./images/part9-search.png)

<br>

- ![part-9hostname](./images/part9-hostname.png)

## Part 10

- ![part10](./images/part10.png)

  name of the hard disk is /dev/sda, its capacity is 10G, number of sectors is 20971520 and swap size is 1.8G

## Part 11

- ![part11-1](./images/part11-1.png)

  partition size is 8408452B\
  space used is 6382128B\
  space free is 1577608B\
  percentage used is 81%

<br>

- ![part11-2](./images/part11-2.png)

  partition size is 8.1G\
  space used is 6.1G\
  space free is 1.6G\
  percentage used is 81% 

## Part 12

- ![part12-1](./images/part12-1.png)

<br>

- ![part12-2](./images/part12-2.png)

## Part 13

- ![part13-1](./images/part13-1.png)

<br>

- ![part13-2](./images/part13-2.png)

<br>

- ![part13-3](./images/part13-3.png)

## Part 14

- ![part14-login](./images/part14-login.png)

  last successful login time is 18:05:47\
  user name is new_user\
  login method is LOGIN(uid=0)\

<br>

- ![part14-sshd](./images/part14-sshd.png)

## Part 15

- ![part15-2-1](./images/part15-2-1.png)

<br>

- ![part15-2-2](./images/part15-2-2.png)

<br>

- ![part15-1](./images/part15-1.png)
  > current jobs for CRON

<br>

- ![part15-3](./images/part15-3.png)
  > no jobs for CRON after removing all tasks