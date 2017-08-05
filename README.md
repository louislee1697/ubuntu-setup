# ubuntu-setup-g470

## [Remap keyboard keys](https://askubuntu.com/questions/133113/emulate-keypad-on-laptop)
Go to Ubuntu Software(Super Key, search "Ubuntu Software"),

## set vi
```
sudo vi ~/.exrc
set nocompatible
set backspace=2
```
Then save the file

## Ansible
```
# install
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible

# run

```

## Import Google's updated GPG Key
Enable update the system without any errors
`wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -`

## apt upgrade
```
sudo apt update
sudo apt dist-upgrade
sudo reboot
```

## AMDGPU-Pro
```
# check if installed 
dpkg -l amdgpu-pro

# install from wget, using -d to send HTTP referrer
wget --referer http://support.amd.com/en-us/kb-articles/Pages/AMDGPU-PRO-Install.aspx https://www2.ati.com/drivers/linux/ubuntu/amdgpu-pro-17.30-458935.tar.xz
wget -d http://www.google.com/
wget -d --header="User-Agent: Mozilla/5.0 (Windows NT 6.0) AppleWebKit/537.11 (KHTML, like Gecko) Chrome/23.0.1271.97 Safari/537.11" --header="Referer: http://xmodulo.com/" --header="Accept-Encoding: compress, gzip" https://www2.ati.com/drivers/linux/ubuntu/amdgpu-pro-17.30-458935.tar.xz
```

