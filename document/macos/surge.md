---
description: 我们对本客户端提供「优先」支持
---

# BMXCloud（新手推荐）

* `系统要求：macOS 10.5 及以上`

### 介绍

BMXCloud For Mac是由斑马线团队为Mac用户推出的一键客户端，您无需进行复杂的配置，内置了最新的GFWList规则，只需登录网站的帐户即可使用。

### 下载

版本:0.1 \| 更新日期: 2018-12-18

[本地下载](https://bmxcloud.cc/dl.php?type=d&id=3) 

### 运行

* 将您下载的压缩包解压到任意目录，点击BMXCloud图标即可启动

### 使用

* 打开软件后点**登录**，在跳出的登录框中填入网站的登录信息，您套餐的节点就会自动更新完成。
* 根据自己网络状况选择合适的节点，点击**全局**或者**PAC模式**，软件会自动配置好系统http代理设置

![](../../.gitbook/assets/image%20%2819%29.png)

* **系统日志**出现以下信息表示V2Ray内核启动成功

![](../../.gitbook/assets/image%20%2817%29.png)

### 设置

软件设置界面里可以自定义端口设置，除非有其他代理工具同时运行造成冲突并清楚知道怎么修改，请尽量保持默认端口配置。默认SOCKS端口1081，HTTP端口8001，PAC服务器端口7777。

### 全局模式与PAC模式

PAC模式需要定期更新规则，并且规则列表臃肿不堪，事实上大量海外并未被干扰的网站，通过代理也能获得更佳的体验，因此推荐使用全局模式来启动HTTP与SOCKS代理，配合SwitchyOmega浏览器插件可以达到最优的浏览体验，[SwitchyOmega使用见进阶教程](https://doc.bmxcloud.cc/pro/windows/switchyomega)。

{% hint style="warning" %}
Chrome和Firefox支持SwithyOmega，但是Safari不支持扩展功能，因此Safari用户请使用默认的系统代理。
{% endhint %}

