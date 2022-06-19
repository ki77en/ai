# ai
An Artix Linux Installer

### About
A fast, simple Artix Linux Installer that uses OpenRC, Linux Zen, Grub & NetworkManager
* Choose drive to install too
* Choose file system, either btrfs/ext4
* Choose to encrypt LVM with LUKS or no encryption at all
* Choose Region
* Setup root password

### How to Use
* Grab the latest Artix Linux OpenRC Base iso
* Launch live CD/USB
* Login using artix,artix
* DO NOT sudo -i, stay as default user within the installer

```
curl -OL https://github.com/ki77en/ai/archive/v1.0.tar.gz
tar xzf v1.0.tar.gz
cd ai-1.0/
./install
```

### Note
This will only work on EFI/UEFI, Legacy boot will not work



