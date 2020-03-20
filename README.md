# my-productivity-tools

- [my-productivity-tools](#my-productivity-tools)
  - [翻墙工具](#%e7%bf%bb%e5%a2%99%e5%b7%a5%e5%85%b7)
  - [终端工具](#%e7%bb%88%e7%ab%af%e5%b7%a5%e5%85%b7)
  - [编辑器](#%e7%bc%96%e8%be%91%e5%99%a8)
  - [浏览器](#%e6%b5%8f%e8%a7%88%e5%99%a8)
  - [开发辅助](#%e5%bc%80%e5%8f%91%e8%be%85%e5%8a%a9)
  - [在线办公](#%e5%9c%a8%e7%ba%bf%e5%8a%9e%e5%85%ac)
  - [日常工具](#%e6%97%a5%e5%b8%b8%e5%b7%a5%e5%85%b7)

## 翻墙工具
Mac下主要使用[ShadowsocksX-NG-R](https://github.com/qinyuhang/ShadowsocksX-NG-R/releases)作为翻墙工具，翻墙源使用[928Net](https://928net.org/)，付费使用，使用了有两年了，网速快+稳定，缺点一个是需要翻墙后才可访问，一个是需要邀请码。

## 终端工具
- [Iterm2](https://github.com/gnachman/iTerm2)：Mac OS X的终端模拟工具，好看+好用
- [OhMyZsh](https://github.com/robbyrussell/oh-my-zsh)：用来美化终端
- [Homebrew](https://brew.sh/index_zh-cn.html)：Mac OS 软件包的管理器

## 编辑器
> 编程专用等宽字体[RobotoMono](https://fonts.google.com/specimen/Roboto+Mono)，你值得拥有
- [Visual Studio Code](https://code.visualstudio.com/)
  - [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)：一个从 Atom 移植的主题，非常简洁好看
  - [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)：为 JS 生成符合 JSDoc 规范的注释工具
  - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)：VSC 中最好用的Git 工具
  - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one): 用来在写 Markdown 的扩展
  - [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client): 比较方便的用来测试和请求API
  - [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)：路径自动补全，引入静态资源的时候必备
  - [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)：好看的文件夹图标
  - [Rainbow Brackets](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)：彩虹括号，缓解眼疲劳
  - [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)：云端开发工具，谁用谁知道
  ```json
  // 将设置放入此文件中以覆盖默认设置
  {
      "editor.fontSize": 16,
      "editor.fontFamily": "RobotoMono-Regular",
      "editor.tabSize": 2,
      "workbench.colorTheme": "One Dark Pro",
      "workbench.iconTheme": "vscode-icons",
      "path-intellisense.mappings": {
        "@": "${workspaceRoot}/src",
      },
      "editor.suggestSelection": "first",
      "remote.SSH.showLoginTerminal": true,
      "window.zoomLevel": 0,
      "javascript.updateImportsOnFileMove.enabled": "always",
      "terminal.integrated.rendererType": "dom"
    }
  ```
- [Jetbrains Toolbox App](https://www.jetbrains.com/toolbox-app/)：使用它管理我的IDEA，Golang，PyCharm
  - [Lombok Plugin](https://github.com/mplushnikov/lombok-intellij-plugin)：Lombok插件
  - [GrepConsole](https://github.com/krasa/GrepConsole)：给日志上色，更好辨认
  - [Alibaba Java Coding Guidelines](https://github.com/alibaba/p3c)：阿里巴巴代码规约检查工具
  - [Free MyBatis plugin](https://plugins.jetbrains.com/plugin/8321-free-mybatis-plugin)：Mybatis 的插件
  - [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)：彩虹括号，缓解眼疲劳

## 浏览器
- [Chrome](https://www.google.com/chrome/)
  - [掘金](https://chrome.google.com/webstore/detail/%E6%8E%98%E9%87%91/lecdifefmmfjnjjinhaennhdlmcaeeeb?utm_source=chrome-ntp-icon)： 为 IT 从业者提供优质内容
  - [OneTab](https://www.one-tab.com/)：标签页管理工具，节省高达95％的内存，并减轻标签页混乱现象
  - [FireShot](https://chrome.google.com/webstore/detail/take-webpage-screenshots/mcbpblocgmgfnpjjppndjkmgjaogfceg?utm_source=chrome-ntp-icon)：网页截图工具
  - [Octotree](https://www.octotree.io/)：Github 代码阅读工具
  - [Google 翻译](https://chrome.google.com/webstore/detail/google-translate/aapbdbdomjkkjkaonfhkkikfgjllcleb)
  - [广告终结者](https://chrome.google.com/webstore/detail/%E5%B9%BF%E5%91%8A%E7%BB%88%E7%BB%93%E8%80%85/fpdnjdlbdmifoocedhkighhlbchbiikl?utm_source=chrome-ntp-icon)
  - [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?utm_source=chrome-ntp-icon)
  - [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?utm_source=chrome-ntp-icon)
- [Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Safari]():系统自带

## 开发辅助
- [Docker](https://www.docker.com/)
- [Navicat Premium](https://www.navicat.com/en/products/navicat-premium)：数据库管理工具
- [Redis Desktop Manager](https://redisdesktop.com/)：Redis管理工具
- [Wireshark](https://www.wireshark.org/)：抓包分析工具
- [Postman](https://www.postman.com/)：接口调试工具

## 在线办公
- [ProcessOn](https://www.processon.com) + [Whimsical](https://whimsical.com)：制作各种图，你指的拥有
- [Balsamiq Mockups 3](https://balsamiq.com/download/)：原型和线框图工具
- [Notion](https://www.notion.so/)：超好用文档工具，缺点就是得翻墙，国内的可以考虑用语雀
- [Carbon](https://carbon.now.sh/)：代码美化工具，还有一个[Codeimg.io](https://codeimg.io/)类似
- [Slides](https://slides.com/)：在线PPT，类似的还有[Beautiful.ai](https://www.beautiful.ai/-Lc9FVBeWUKROplVtvz4/1)和[Google Presentation](https://docs.google.com/presentation)，看个人喜好
- [Google Office](https://docs.google.com/)：Google出的在线Doc，Excel，PPT工具，国内的有腾讯文档可以替代

## 日常工具
- [1Password](https://1password.com/)
- [有道词典](http://dict.youdao.com/)
- [每日英语听力](http://dict.eudic.net/ting/)
- [微信](https://weixin.qq.com/)
- [百度网盘](https://pan.baidu.com/)
- [PDF Expert](https://www.pdfexpert.cn/)
- [Alfred3](https://www.alfredapp.com/)：Mac最好的效率工具
- [CleanMyMac](https://cleanmymac.com/)：Mac清理工具
- [Archiver](https://archiverapp.com/)：解压缩工具
- [Paste](https://pasteapp.com/)：剪贴板记录工具
- [Magnet](https://itunes.apple.com/cn/app/p.m.-magnet-free/id441258766?mt=12)：快捷分屏工具
- [IINA](https://github.com/lhc70000/iina)：Mac中比较好用的现代播放器
- [Clear My Mac](https://macpaw.com/)：Mac清理工具
- [iStat Menus](https://bjango.com/mac/istatmenus/)：电脑运行状态监控工具
