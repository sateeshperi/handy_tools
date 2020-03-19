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
