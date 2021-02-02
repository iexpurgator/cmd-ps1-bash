# SSH

## Transfer file Windows to Linux

0. On linux install `ssh` & `openssh-server`. check open port `openssh-server` using `sudo service ssh status`
1. Open `powershell` on windows. Using:<br> `scp -r Disk:\dir\to\file linux_username@linux_hostname_or_local_ip:/remote/directory/on/linux/pc`

## Transfer file Linux to Window

0. On linux install `ssh` & `openssh-server`. check open port `openssh-server` using `sudo service ssh status`
1. Open `powershell` on windows. Using:<br> `scp linux_username@linux_hostname_or_local_ip:/remote/directory/on/linux/file`
