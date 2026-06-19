## Hi there 👋

<!--TODO: 中文版-->

Some toy projects I made:

### Web apps
- [myflaskserver](https://github.com/barryZZJ/myflaskserver):
  
  A Flask-based personal gateway service. It is mainly used as a endpoint for responding my WeCom bot messages, with some other features like a small DDNS-style redirect dashboard, and exposing webhook endpoints for [FreshrssCrawler](https://github.com/barryZZJ/freshrsscrawler). Also include two WeCom bots: `TVSubscriberBot` for subscribing TV programs and `DrinkBot` for recording daily drink intake. Both bots support interactive queries and scheduled tasks.
  
  - [TVSubscribeBot](https://github.com/zhimengsub/TVSubscribeBot):

    Example usage of `dumb_bot` that queries and subscribe tv programs. The bot interactively ask for tv information like channel name and program title then subscribe that program. Also supports scheduled queries.
    
  - [dumb_bot](https://github.com/barryZZJ/dumb_bot):

    A platform-independent bot that is interacted purely based on string. Supports chained commands and positional args like `/cmd subcmd args kwarg=val`, and interactive conversations. Improved and pruned based on telegrambot.
    
- [wecombots](https://github.com/barryZZJ/wecombots):

  A collection of small automated WeCom bots, including website check-in helpder with captcha solvers.
  - [wecomsan](https://github.com/barryZZJ/wecomsan):
    
    A Python wrapper for wecom APIs. Used by all my wecombot-related projects.

### Web Crawling / Automation

- Tampermonkey scripts (Web browser extension for running custom JavaScripts.)

  - [ucas_class_enrollment_assistant](https://github.com/barryZZJ/ucas_class_enrollment_assistant)
  - [CQU_class_select_helper](https://github.com/barryZZJ/CQU_class_select_helper)

    Assist class enrollments.
    
  - [lemonedo_downloader](https://github.com/barryZZJ/lemonedo_downloader)

    Resolve hidden download links and add download buttons.

- [RSSHub](https://github.com/barryZZJ/RSSHub)

  I added support for crawling and generating RSS feeds for a few hosts, such as [this](https://github.com/barryZZJ/RSSHub/tree/8982f705cb5402f1caa02deb078f03862f23778b/lib/routes/kamishiraishimone) and [this](https://github.com/barryZZJ/RSSHub/tree/8982f705cb5402f1caa02deb078f03862f23778b/lib/routes/gamersky).
  
- [ucas_course_to_calendar](https://github.com/barryZZJ/ucas_course_to_calendar):

  An web crawling automation script that reads your course schedule and convert them to .ics files to be imported to mobile phone.

- [ucas_cronavirus_report](https://github.com/barryZZJ/ucas_cronavirus_report)
- [CQU_crona_auto_report](https://github.com/barryZZJ/CQU_crona_auto_report)

  Scripts for automatically making check-in reports.

### Automation tools

- [minesweeper_classic](https://github.com/barryZZJ/minesweeper_classic):

  A MineSweeper game based on pyqt5 that simulates classic minesweeper game interface. With a customized solver algorithm and a DQN model solver.

- [SubtitleCleaner](https://github.com/zhimengsub/SubtitleCleaner):

  An CLI automation tool that clean closed captions of tv programs.
  
- [TorrentUploader](https://github.com/zhimengsub/TorrentUploader):

  An GUI automation tool that monitors and creates torrents for local files, and automatically publish them to BT sites.

- [portprotector](https://github.com/barryZZJ/portprotector):

  Used on server as a crontab task. Monitors connections made to specified ports, block and log their info to a table if connections were made too often.


### My papers / AI related
- [grad_guide_fl_attack](https://github.com/barryZZJ/grad_guide_fl_attack):

  Data reconstruction attack in Federated Learning based on Inference-time Conditional Diffusion Models.

### Hardware

- [Hardware_Design](https://github.com/barryZZJ/Hardware_Design):

  MIPS five-level pipeline CPU based on Verilog.

### Misc

- [Notes](https://github.com/barryZZJ/Notes):
  
  Notes taken based on my everyday knowledge accumulated gradually. Only made public temporarily for showcase.

- [wol](https://github.com/barryZZJ/wol):

  An asus router plugin of koolshare firmware that fixes the original feature of sending WOL (wake on lan) packets.
