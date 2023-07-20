# ![OsamaNawab](https://i.ibb.co/B2WLYt2/Osama-Nawab.jpg) Golang

 [![](https://img.shields.io/badge/Go1.20.4.Linux%20amd64-blue.svg )](https://go.dev/dl/go1.20.4.linux-amd64.tar.gz) [![](https://img.shields.io/badge/MIT%20License-Version%202.0-red.svg )]()
 
## *Golang Auto Installation In Linux*
---
# Requirements 

## Linux
Kernel version 2.6.32 or later. Linux/ARMv5 requires much newer kernels, at least v3.1(for Kuser Cmpxchg64)

We don't support CentOS 5. The kernel is too old (2.6.18).

## VPS (Virtual Private Server)
 
Ubuntu 22.04.2 LTS (GNU/Linux 64 *&* x86)

# Installation

Installation is simple. It can be installed from using the following command:
```
$ sudo apt update && sudo apt upgrade -y
$ sudo apt install zip unzip -y
$ unzip installgo.zip
$ chmod +x installgo && chmod +x installgomod
$ ./installgo
$ GOROOT=/usr/local/go && GOPATH=$HOME && PATH=$GOPATH/bin:$GOROOT/bin:$PATH
$ go env -w GO111MODULE=off
$ ./installgomod
```


### Author
[Line](line://nv/profilePopup/mid=ub5901af75404384703c8937a9287b836)

[Telegram](https://t.me/OsamaNawab)
