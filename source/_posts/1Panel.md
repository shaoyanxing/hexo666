---
title: 1Panel面板安装教程
date: 2024-08-24 17:49:06
tags: [折腾, 闲着, 极简教程]
---
### 1Panel面板安装教程

![image-20240824184524773](https://pic.shaoyanxing.top/i/2024/08/24/66c9b9d00851d.png)

<!-- TOC -->

- [Panel面板安装教程](#panel%E9%9D%A2%E6%9D%BF%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B)
    - [引言](#%E5%BC%95%E8%A8%80)
    - [快速上手](#%E5%BF%AB%E9%80%9F%E4%B8%8A%E6%89%8B)
        - [登录到1Panel面板后台](#%E7%99%BB%E5%BD%95%E5%88%B01panel%E9%9D%A2%E6%9D%BF%E5%90%8E%E5%8F%B0)

<!-- /TOC -->

#### 引言
欢迎来到“极简”系列教程，在这里，我们不会把你淹没在专业术语的汪洋和繁琐步骤中。相反，我们将通过简洁易懂的指导，让看起来复杂的技术世界变得近在咫尺。
今天，我来教大家安装1Panel面板。

#### 快速上手

[1Panel官网]([1Panel - 现代化、开源的 Linux 服务器运维管理面板](https://1panel.cn/))提供了一键安装脚本，我们只需将代码贴进ssh窗口就行了!

**请复制对应你的`Liunx`版本的代码，请看仔细！**

|      Liunx版本      |                             代码                             |
| :-----------------: | :----------------------------------------------------------: |
| **RedHat / CentOS** | `curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && sh quick_start.sh` |
|     **Debian**      | `curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && bash quick_start.sh` |
|     **Ubuntu**      | `curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && sh quick_start.sh` |


**之后会让你配置，一直回车即可。最后，会给你IP:端口/安全入口和用户名密码。**

##### 登录到1Panel面板后台

1Panel面板地址：http://你的服务器IP地址:端口/安全入口
**举例说明**：服务器网的IP地址为123.123.123.123，端口为20410，安全入口为shoayanxing，所以我的1Panel登录地址如下：
http://123.123.123.123:20410/shoayanxing
之后会打开这样的页面：

![image-20240824185307837](https://pic.shaoyanxing.top/i/2024/08/24/66c9bb96b9bd1.png)

输入用户名和密码即可登录。

**感谢你的阅读！**
