# Learning-Diary-of-LaTex
keywords:Learning Diary of LaTex

关键词：LaTex学习日记
## LaTex Install
### Windows
- 环境：Win10(20H2)

- 目标/特点：搭建LaTex本地环境，用以论文、报告等写作，更加私密/安全，但所需硬盘空间较大，不利于多人协作

#### 相关工具：

- LaTex发行版:TexLive  

- 编辑器:[Visual Studio Code]([Download Visual Studio Code - Mac, Linux, Windows](https://code.visualstudio.com/download))

- 阅读器：[Sumatra PDF ]([Download Sumatra PDF - a free reader (sumatrapdfreader.org)](https://www.sumatrapdfreader.org/download-free-pdf-viewer))

- 下载工具：[Google Chrome]([Google Chrome 网络浏览器](https://www.google.com/intl/zh-CN/chrome/)) / [Microsoft Edge](https://www.microsoft.com/en-us/edge) / [Mozila Firefox]([下载 Firefox 浏览器 — 快速、私密、免费 — 来自 Mozilla](https://www.mozilla.org/zh-CN/firefox/new/)) + [Free Download Manager]([Free Download Manager - 從網路下載任何東西](https://www.freedownloadmanager.org/zh/)) + [Free Download Manager extension](https://chrome.google.com/webstore/detail/free-download-manager/ahmpjcflkgiildlgicmcieglgoilbfdp)

#### 安装步骤如下

##### 1.下载TexLive

- TexLive主页：https://www.tug.org/texlive/

- 安装下载地址：https://www.tug.org/texlive/acquire-netinstall.html

- 但基于国内网络环境，建议采用镜像网站下载，相关镜像网站列表见
https://ctan.org/mirrors

- 这里推荐清华镜像：[Index of /CTAN/systems/texlive/Images/ | 清华大学开源软件镜像站 | Tsinghua Open Source Mirror](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images/)

- 进入网页后，选择最新镜像，利用Free Download Manager extension 下载（具体添加扩展可以通过Free Download Manager 软件选项-浏览器集成 添加至相应浏览器）

- 具体操作为单击右键，选择Download with Free Download Manager，如下图所示

![Texlive-Tshinghua](https://github.com/maxwellknown/Learning-Diary-of-LaTex/raw/main/pic/Texlive-Tshinghua.png "TexLive Tshinghua-mirroor")

- 下载完成后，可利用md5校验工具等校验iso镜像文件，确保下载的完整性

##### 2.安装TexLive
- 打开texlive.iso，进入目录找到install-tl-windows.bat（可用右键，管理员模式打开避免权限问题）点击安装界面的`Advanced`按钮，查看安装路径，注意将Texlive安装至英文目录下

- 默认安装即可，此过程可能耗时数小时。
安装完成后，打开cmd，输入以下命令
`tex -version`检查，若返回版本信息，即安装成功。

- 检查安装路径是否添加至环境变量（如何添加环境变量）
### Linux
