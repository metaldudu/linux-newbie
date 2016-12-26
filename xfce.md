# Xfce桌面环境

Xfce是与传统Windows桌面很接近的一个**桌面环境**，安装完毕的 Xfce，看上去就像是Windows95。相对而言，Xfce 占用系统资源比较少，属于轻量的桌面环境。

Xfce包含在很多发行版里面，比如 Xubuntu，Manjaro Linux。

## Xfce的功能

* 窗口
* 桌面
* 文件管理
* 会话
* 

## Xfce的安装和配置

安装xorg和xfce，以 Archlinux 为例：

    # pacman -S xorg-server xorg-xinit xorg-server-utils
    # pacman -S xfce4 xfce4-goodies


## 快捷键

在 `Settings -> Keyboard -> Application Shortcuts` 中，可以设置快捷键。这里可以看到系统默认的快捷键，比如：

* xfce4-appfinder: Alt+F2
* xfce4-appfinder --collapsed: Alt+F3

这两组快捷键可以打开 Xfce 内置的程序：Application Finder，可以迅速打开已经安装的程序。


## 自定义快捷键

比如，我们给文本编辑器“mousepad”增加一个快捷键为 “Win + N”，操作如下：

* 点击 Add，在 Command 输入框内输入"mousepad"
* 按照提示，按下组合键




---

#### 相关链接

* [https://www.xfce.org/](https://www.xfce.org/)