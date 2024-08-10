---
title: 如何在「Fedora」安裝「Cosmic Desktop」
nav_order: 7011
has_children: false
parent: 如何
---


# 如何在「Fedora」安裝「Cosmic Desktop」

* [參考文件](#參考文件)
* [操作步驟](#操作步驟)




## 參考文件

在「[Cosmic Desktop Environment](https://system76.com/cosmic)」這一頁，

可以找到「`Try it out on your favorite distro!`」，

其中有「`Fedora - See instructions`」

就會連結到「[COSMIC Desktop Environment for Fedora](https://copr.fedorainfracloud.org/coprs/ryanabx/cosmic-epoch/)」這一頁。

就可以找到如下的「[操作步驟](#操作步驟)」，在「Fedora」安裝「Cosmic Desktop」。




## 操作步驟

先執行

``` sh
sudo dnf copr enable ryanabx/cosmic-epoch
```

接著再執行下面指令，安裝「`cosmic-desktop`」。

``` sh
sudo dnf install cosmic-desktop
```
