# vbox-ubuntu-server

Install VirtualBox Guest Additions inside Ubuntu 20.04 Server version

```
sudo mount /dev/cdrom /mnt

cd /mnt

sudo apt-get install -y build-essential dkms linux-headers-$(uname -r)
```

```
sudo ./VBoxLinuxAdditions.run
```
