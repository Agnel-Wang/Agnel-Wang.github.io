---
sort: 2
---

# Linux安装

由于ROS开发需求，一直以来都采用Ubuntu版。

## Ubuntu安装

转载：https://zhuanlan.zhihu.com/p/135953477

1. 制作启动U盘

- 下载镜像
```
官网下载
https://www.ubuntu.com/download
清华大学镜像站下载
https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/18.04/
```

- 下载U盘制作软件
```
rufus
https://rufus.ie/
```

2. 安装

进入BIOS界面，选择U盘启动，正常安装。

平时：此时未设置Swap分区

- software & update 里面更新源，选择清华大学源

### 环境配置

<div style="text-align: center;">
<table border='1' style="margin: auto">
    <tr>
        <th colspan='3'>sudo apt install</th>
    </tr>
    <tr>
        <td>gdebi</td><td>cmake</td><td>vim</td>
    </tr>
    <tr>
       <td>curl</td><td>build-essential</td><td>openssh-server</td>
    </tr>
</table>
</div>

sudo /etc/init.d/ssh start

### 软件安装


#### Github-desktop

```
sudo wget https://github.com/shiftkey/desktop/releases/download/release-2.9.3-linux3/GitHubDesktop-linux-2.9.3-linux3.deb
sudo gdebi GitHubDesktop-linux-2.9.3-linux3.deb
```

#### Qt

#### ROS

目前安装的是18.04，借鉴于

https://www.guyuehome.com/35121

ROS2待定

#### VSCode 

应用商店搜索code
