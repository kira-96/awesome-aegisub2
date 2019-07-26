# Aegisub 安装说明

---

### 下载

目前最新正式版本为**3.2.2**，可以在[官网](http://www.aegisub.org/)进行[下载](http://www.aegisub.org/downloads/)

但由于已经多年没有更新，在一些系统上可能会出现莫名其妙的问题，如过遇到问题，可以尝试使用[开发版本](http://plorkyeran.com/aegisub/)

> 即使在64位Windows系统上也不建议使用64位的Aegisub。因为64位Aegisub不支持Avisynth，并且可能比32位有更多bugs。

> 目前已知3.2.2版本在最近的OSX系统上存在音频显示不正确的问题，开发版本已经解决了该问题，建议OSX用户下载[开发版本](http://plorkyeran.com/aegisub/)使用

### 安装

Windows和OSX系统直接下载相应系统的安装包安装即可。

Linux系统用户可以尝试以下方式

- 源码

可以去[Aegisub官网](http://www.aegisub.org/)下载源码自行编译，大佬们请自行测试

- 通过[developer’s PPA](https://launchpad.net/~alex-p/+archive/ubuntu/aegisub)

参考自[How to Install Aegisub Subtitle Editor in Ubuntu 18.04](http://ubuntuhandbook.org/index.php/2018/08/how-to-install-aegisub-subtitle-editor-in-ubuntu-18-04/)

```bash
# install
sudo add-apt-repository ppa:alex-p/aegisub
sudo apt-get install aegisub

# uninstall
sudo add-apt-repository --remove ppa:alex-p/aegisub
sudo apt-get remove --autoremove aegisub
```

- deepin应用商店

顺便安利一个非常漂亮、非常好用的Linux发行版[deepin](https://www.deepin.org/)

可以直接在系统自带的应用商店里找到Aegisub，直接安装即可

- 多语言

```bash
sudo apt install aegisub-l10n
```

然后在软件界面选择**View -> Language**选择要切换的语言

deepin系统亲测有效

最后欢迎各位群友进行测试，指正。


