# setup for new ubunutu on mac

- [Install broadcom driver offline](https://askubuntu.com/questions/730799/installing-firmware-b43-installer-offline/730813#730813)

- [Install R 3.6](deb http://cran.wustl.edu/bin/linux/ubuntu bionic-cran35/)
  + `sudo nano /etc/apt/sources.list`
  + `sudo apt update`
  + `sudo apt install r-base`

- [Rstudio download page](https://rstudio.com/products/rstudio/download/#download)


### icommands
```
wget https://files.renci.org/pub/irods/releases/4.1.10/ubuntu14/irods-icommands-4.1.10-ubuntu14-x86_64.deb
apt-get install ./irods-icommands-4.1.10-ubuntu14-x86_64.deb
```

### *** Install Miniconda3 for 64-bit Linux ***
```
curl https://repo.continuum.io/miniconda/Miniconda3-4.7.12.1-Linux-x86_64.sh -O
bash Miniconda3-4.7.12.1-Linux-x86_64.sh
rm Miniconda3-4.7.12.1-Linux-x86_64.sh
```
