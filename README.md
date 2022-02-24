# iOS_Slices
一些开发过程中碰到的小问题，以及解决办法，记录用:

### MacOS Monterry的隐私，如何允许“任何来源”
显示允许任何来源: `sudo spctl --global-disable`
隐藏允许任何来源: `sudo spctl --global-enable`
参考链接: [https://developer.apple.com/forums/thread/670610](https://developer.apple.com/forums/thread/670610)

### zsh和bash的想换切换

1、 查看当前使用的是哪个？
   `echo $SHELL`
2、 分别查看zsh和bash的安装路径
   `which zsh`
   `which bash`
3、zsh切换到bash
   `chsh -s /bin/bash`
4、bash切换到zsh
   `chsh -s /bin/zsh`
5、重启终端或者使用source生效
