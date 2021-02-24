## testing  
  
DESCRIBE  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/testing/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install testing
```  

Fedora Based:

```shell
yum install testing
```  

Arch Based:

```shell
pacman -S testing
```  

MacOS:  

```shell
brew install testing
```
  
```shell
mv -fv "$HOME/.config/testing" "$HOME/.config/testing.bak"
git clone https://github.com/dfmgr/testing "$HOME/.config/testing"
```
  
<p align=center>
   <a href="https://travis-ci.com/github/dfmgr/testing" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/dfmgr/testing.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/testing" target="_blank" rel="noopener noreferrer">testing wiki</a>  |  
  <a href="testing" target="_blank" rel="noopener noreferrer">testing site</a>
</p>  
