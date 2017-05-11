# asOnUbuntuInstall.sh

- set permissions with: chmod 0755 asOnUbuntuInstall.sh
- then run with ./asOnUbuntuInstall.sh
- taken from https://www.linuxbabe.com/ubuntu/install-android-studio-ubuntu-16-04

```
# Install Java 8
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update -y
sudo apt-get install java-common oracle-java8-installer -y
sudo apt-get install oracle-java8-set-default -y
source /etc/profile

# Installing Android Studio in Ubuntu 16.04 via PPA 
sudo add-apt-repository ppa:maarten-fonville/android-studio
sudo apt update -y
sudo apt install android-studio -y
```
