# PRemoteM

[English](https://github.com/VShawn/PRemoteM#PRemoteM) | 中文

<p align="center">
    <img src="https://github.com/VShawn/PRemoteM/raw/Doc/DocPic/PRemoteM.png" width="50" />
</p>

```
PRemoteM = Personal Remote Manager
```

PRemoteM 是一款现代的远程会话管理器和启动器，它让你能够在任何时候快速开启一个远程会话。目前 PRemoteM 已支持 RDP、VNC、SSH、Telnet、sFtp等多种协议。

<p align="center">
    快速启动器(alt+M)
</p>

<p align="center">
    <img src="https://github.com/VShawn/PRemoteM/raw/Doc/DocPic/quickstart.gif" width="600"/>
</p>

<p align="center">
    Tab 分离与SSH连接后自动执行指令
</p>
<p align="center">
    <img src="https://github.com/VShawn/PRemoteM/raw/Doc/DocPic/tab.gif" width="600"/>
</p>

<p align="center">
    RDP多显示器全屏模式
</p>
<p align="center">
    <img src="https://github.com/VShawn/PRemoteM/raw/Doc/DocPic/multi-screen.jpg" width="700"/>
</p>


## 特性

----
- 快捷方便的远程会话启动器，支持拼音检索汉字
- 目前唯一一款支持 RDP 多显示器远程管理的第三方工具。(测试基于 **Win10 + 4k显示器*2** 远程至 **Win2016**)
- 基于 PuTTY 的 SSH、Telnet 会话，支持连接后自动执行指令。
- [可从 mRemoteNG 迁移会话](https://github.com/VShawn/PRemoteM/blob/Doc/ReadMe_zh-cn/readme.md#从-mRemoteNG-迁移数据)
- [基于 RSA 的敏感数据保护](https://github.com/VShawn/PRemoteM/blob/Doc/ReadMe_zh-cn/readme.md#数据加密)

# Lastet

最新版本: 0.5.1.2011261907

- [下载](https://github.com/VShawn/PRemoteM/releases)
  
## 系统要求

----

- [.NET Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48)

## 使用方法

----

### 启动远程会话

1. 运行 PRemote.exe.

2. 通过 "+" 按钮新增远程会话信息

3. 通过双击 **会话卡片** 以开启一个远程会话

4. 或者你可以通过 <kbd>Alt</kbd> + <kbd>M</kbd> 打开快速启动器键入关键字并回车以启动远程会话

### 数据加密

数据加密后，即便你的数据库被非法窃取，偷窃者在未获得私钥的情况下也无法得到你的敏感数据。
设置方法：

1. 在 <kbd>设置</kbd> -> <kbd>数据与安全</kbd> 界面
2. 点击 <kbd>生成加密</kbd> 按钮后，你的数据将被加密，请将生成的**私钥**妥善保管.

<p align="center">
    <img src="https://github.com/VShawn/PRemoteM/raw/Doc/DocPic/Encryption.jpg" width="300"/>
</p>

### 从 mRemoteNG 迁移数据

<p align="center">
    <img src="https://github.com/VShawn/PRemoteM/raw/Doc/DocPic/Migrate.jpg"/>
</p>

## 添砖加瓦

1. 提出新的改进点，包括但不限于提Bug、提新需求、设计、交互建议。

2. 帮助翻译，复制一份[en-us.js](https://github.com/VShawn/PRemoteM/blob/dev/PRM.Core/Languages/en-us.json)，将其中的英文翻译成其他语言 Pull request 给我。

3. 帮写文档（~~写文档真是太痛苦了~~），现在需要帮写使用说明、翻译文档等工作，我主要把时间分配给功能实现上了，文档上常常跟不上新功能。

4. 欢迎捐赠

<p align="center">
    <img src="https://github.com/VShawn/PRemoteM/raw/Doc/DocPic/others/donate.jpg"/>
</p>