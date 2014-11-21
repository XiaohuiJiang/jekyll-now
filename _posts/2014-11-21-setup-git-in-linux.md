---
layout: post
title: set up git in linux for github
---

```

   16  mkdir github
   17  cd github/
   18  sudo
   19  sudo  apt-get install git
   20  git
   21  git --version
   22  git config --global user.name "XiaohuiJiang"
   23  git config --global user.email "XiaohuiJiang@users.noreply.github.com"
   24  git config
   25  ls -la
   26  ls -la ~
   27  cat ~/.gitconfig 
   28  git credential-osxkeychain
   29  curl -s -O https://github-media-downloads.s3.amazonaws.com/osx/git-credential-osxkeychain
   30  sudo apt-get install curl
   31  curl -s -O https://github-media-downloads.s3.amazonaws.com/osx/git-credential-osxkeychain
   32  ls
   33  sudo apt-get install curl
   34  chmod u+x git-credential-osxkeychain
   35  ls -l git-credential-osxkeychain 
   36  which git
   37  dirname $(which git)
   38  sudo mv git-credential-osxkeychain "$(dirname $(which git))/git-credential-osxkeychain"
   39  ls
   40  ls /usr/bin/git*
   41  ls /usr/bin/
   42  ls -l /usr/bin/py*
   43  ruby --version
   44  git config --global credential.helper osxkeychain

```
