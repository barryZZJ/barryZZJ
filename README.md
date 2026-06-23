## Hi there 👋

[中文](#中文) | [English](#english)

<a id="english"></a>

Some toy projects I made:

### Web apps
- [myflaskserver](https://github.com/barryZZJ/myflaskserver):
  
  A Flask-based personal web service. It is mainly used as an endpoint for responding my WeCom bot messages, with some other features like a dashboard for redirecting to all web services I have deployed, and exposing webhook endpoints for [FreshrssCrawler](https://github.com/barryZZJ/freshrsscrawler). Also include two WeCom bots: `TVSubscriberBot` for subscribing TV programs and `DrinkBot` for recording daily drink intake. Both bots support interactive queries and scheduled tasks.
  
  - [TVSubscribeBot](https://github.com/zhimengsub/TVSubscribeBot):

    Example usage of [`dumb_bot`](https://github.com/barryZZJ/dumb_bot) that queries and subscribe tv programs. The bot interactively ask for tv information like channel name and program title then subscribe that program. Also supports scheduled queries.
    
  - [dumb_bot](https://github.com/barryZZJ/dumb_bot):

    A platform-independent bot framework that is interacted purely based on string. Developed new supports on (infinite) subcommands and keyword args like `/cmd subcmd args kwarg=val`. Improved and pruned based on telegrambot.
    
- [wecombots](https://github.com/barryZZJ/wecombots):

  A collection of small automated WeCom bots, including website check-in helpder with clicking captcha solvers.

  - [wecomsan](https://github.com/barryZZJ/wecomsan):
    
    A Python wrapper for wecom APIs. Used by all my wecombot-related projects.

### Web Crawling / Automation

- Tampermonkey scripts (Tampermonkey is a Web browser extension for running custom JavaScripts)

  - [ucas_class_enrollment_assistant](https://github.com/barryZZJ/ucas_class_enrollment_assistant)
  - [CQU_class_select_helper](https://github.com/barryZZJ/CQU_class_select_helper)

    Assist class enrollments.
    
  - [lemonedo_downloader](https://github.com/barryZZJ/lemonedo_downloader)

    Resolve hidden download links and add download buttons.

- [RSSHub](https://github.com/barryZZJ/RSSHub)

  I added support for crawling and generating RSS feeds for a few hosts, such as [this](https://github.com/barryZZJ/RSSHub/tree/8982f705cb5402f1caa02deb078f03862f23778b/lib/routes/kamishiraishimone) and [this](https://github.com/barryZZJ/RSSHub/tree/8982f705cb5402f1caa02deb078f03862f23778b/lib/routes/gamersky) and so on.
  
- [ucas_course_to_calendar](https://github.com/barryZZJ/ucas_course_to_calendar):

  An web crawling automation script that reads your course schedule and convert them to .ics files to be imported to mobile phone.

- [ucas_cronavirus_report](https://github.com/barryZZJ/ucas_cronavirus_report)
- [CQU_crona_auto_report](https://github.com/barryZZJ/CQU_crona_auto_report)

  Scripts for automatically making check-in reports.

### Automation tools

- [minesweeper_classic](https://github.com/barryZZJ/minesweeper_classic):

  A MineSweeper game based on pyqt5 that simulates classic minesweeper game interface, with a customized solver algorithm and a DQN model solver.

- [SubtitleCleaner](https://github.com/zhimengsub/SubtitleCleaner):

  An CLI automation tool that clean closed captions of tv programs.
  
- [TorrentUploader](https://github.com/zhimengsub/TorrentUploader):

  An GUI automation tool that monitors and creates torrents for local files, and automatically publish them to BT sites.

- [portprotector](https://github.com/barryZZJ/portprotector):

  Used as a crontab task on servers. Monitors connections made to specified ports, block and log their info to a table if connections were made too often.


### My papers / AI related
- [grad_guide_fl_attack](https://github.com/barryZZJ/grad_guide_fl_attack):

  Data reconstruction attack in Federated Learning based on Inference-time Conditional Diffusion Models.

### Hardware Simulation

- [Hardware_Design](https://github.com/barryZZJ/Hardware_Design):

  MIPS five-level pipeline CPU based on Verilog.

### Misc

- [Notes](https://github.com/barryZZJ/Notes):
  
  A collection of notes gradually accumulated from everyday learning over my entire life. Temporarily public for showcase purposes.

- [wol](https://github.com/barryZZJ/wol):

  An asus router plugin of koolshare firmware that fixes the original feature of sending WOL (Wake-on-LAN) packets.

---


[中文](#中文) | [English](#english)

<a id="中文"></a>

我做过的一些玩具项目：

### Web 应用
- [myflaskserver](https://github.com/barryZZJ/myflaskserver):
  
  一个基于 Flask 的个人网络服务。主要作为企业微信机器人的消息回复端，同时也包含一些其他功能如 自建服务重定向 Dashboard，以及为 [FreshrssCrawler](https://github.com/barryZZJ/freshrsscrawler) 暴露 webhook 接口。项目还包含两个企业微信机器人：`TVSubscriberBot` 用于订阅电视节目，`DrinkBot` 用于记录每日饮水量。两个机器人都支持交互式查询和定时任务。
  
  - [TVSubscribeBot](https://github.com/zhimengsub/TVSubscribeBot):

    [`dumb_bot`](https://github.com/barryZZJ/dumb_bot) 的一个实际用例，用于查询和订阅电视节目。机器人会通过交互方式询问频道名、节目标题等电视节目信息，然后订阅该节目；同时也支持定时自动查询。
    
  - [dumb_bot](https://github.com/barryZZJ/dumb_bot):

    一个不依赖通信应用平台的机器人框架，纯基于字符串进行交互。开发(无限)链式子命令、键值参数功能，例如 `/cmd subcmd args kwarg=val`，以及交互式对话。基于 telegrambot 改进和精简而来。
    
- [wecombots](https://github.com/barryZZJ/wecombots):

  一组小型自动化企业微信机器人，包括带点击验证码识别的网站签到助手。

  - [wecomsan](https://github.com/barryZZJ/wecomsan):
    
    一个企业微信 API 的 Python 封装，我所有企业微信机器人相关项目都在使用。

### 网页爬取 / 自动化

- Tampermonkey 脚本（Tampermonkey 是用于运行自定义 JavaScript 的浏览器扩展）

  - [ucas_class_enrollment_assistant](https://github.com/barryZZJ/ucas_class_enrollment_assistant)
  - [CQU_class_select_helper](https://github.com/barryZZJ/CQU_class_select_helper)

    辅助抢课。
    
  - [lemonedo_downloader](https://github.com/barryZZJ/lemonedo_downloader)

    解析隐藏下载链接并添加下载按钮。

- [RSSHub](https://github.com/barryZZJ/RSSHub)

  我为一些站点添加了爬取和生成 RSS 源的支持，例如[这个](https://github.com/barryZZJ/RSSHub/tree/8982f705cb5402f1caa02deb078f03862f23778b/lib/routes/kamishiraishimone)和[这个](https://github.com/barryZZJ/RSSHub/tree/8982f705cb5402f1caa02deb078f03862f23778b/lib/routes/gamersky)等等。
  
- [ucas_course_to_calendar](https://github.com/barryZZJ/ucas_course_to_calendar):

  一个网页爬取自动化脚本，用于读取课程表并转换为可导入手机日历的 .ics 文件。

- [ucas_cronavirus_report](https://github.com/barryZZJ/ucas_cronavirus_report)
- [CQU_crona_auto_report](https://github.com/barryZZJ/CQU_crona_auto_report)

  自动打卡脚本。

### 自动化工具

- [minesweeper_classic](https://github.com/barryZZJ/minesweeper_classic):

  一个基于 pyqt5 的扫雷游戏，模拟经典扫雷界面，并包含自定义求解算法和 DQN 模型求解器。

- [SubtitleCleaner](https://github.com/zhimengsub/SubtitleCleaner):

  一个用于清理电视节目台词字幕的命令行自动化工具。
  
- [TorrentUploader](https://github.com/zhimengsub/TorrentUploader):

  一个 GUI 自动化工具，用于监控本地文件、创建种子，并自动发布到 BT 站点。

- [portprotector](https://github.com/barryZZJ/portprotector):

  作为服务器上的 crontab 任务使用。监控指定端口的连接，如果连接过于频繁，则阻断并将连接信息记录到表格中。


### 我的论文 / AI 相关
- [grad_guide_fl_attack](https://github.com/barryZZJ/grad_guide_fl_attack):

  基于推理时条件扩散模型的联邦学习数据重建攻击。

### 硬件仿真

- [Hardware_Design](https://github.com/barryZZJ/Hardware_Design):

  基于 Verilog 的 MIPS 五级流水线 CPU。

### 其他

- [Notes](https://github.com/barryZZJ/Notes):
  
  包含了所有我日常积累的知识，逐步整理形成的笔记。临时公开用于展示。

- [wol](https://github.com/barryZZJ/wol):

  一个适用于 koolshare 固件的华硕路由器插件，用于修复原有 WOL（Wake-on-LAN）发包功能。
