# Linux系统下

* python3.6+

* ubuntu 16.04/18.04

* PyChame IDE

* 谷歌浏览器\(别用最新版\)

* 推荐使用Miniconda虚拟环境管理工具

---

## Windows系统下

* python3.6+
* win7专业版以上版本
* PyChame IDE
* 谷歌浏览器
* 推荐使用Miniconda虚拟环境管理工具

---

### Miniconda的安装

下载网站链接：[https://docs.conda.io/en/latest/miniconda.htm](https://docs.conda.io/en/latest/miniconda.html)

![](/assets/Miniconda.png)

1. 如图根据自己的电脑系统选择miniconda的版本，注意使用python3.6+，python2.7+已经过时不建议使用
2. windows系统下下载的是".exe"文件点击安装即可，Linux系统下下载的是".sh"文件，需要使用终端切换到当前文件的路径输入"bash xxx.sh"\(xxx是你下载的文件名\)，然后一直Enter键，直到出现下面图片中的选项，输入yes，直到安装结束![](/assets/13094796-4c0cfceb1150a54f.png)
3. 检查安装在终端中输入"canda --version"出现版本号即安装成功

#### Miniconda的入门使用

有问题更新miniconda：conda env update -f environment.yml

创建一个新的conda环境 conda create -n env-name python=版本号

运行环境：source activate env-name

关闭环境：source deactivate env-name

导出包管理配置：conda env export -n env-name

查看已有环境：conda info -e

更新 conda 本身源 conda update conda

 

---

## Linux下chrome安装

* sudo wget [http://www.linuxidc.com/files/repo/google-chrome.list](http://www.linuxidc.com/files/repo/google-chrome.list) -P /etc/apt/sources.list.d/
* wget -q -O -[https://dl.google.com/linux/linux\_signing\_key.pub](https://dl.google.com/linux/linux_signing_key.pub) \| sudo apt-key add -
* sudo apt-get update
* sudo apt-get install google-chrome-stable
* /usr/bin/google-chrome-stable \# 启动chrome



