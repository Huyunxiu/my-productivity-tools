# my-productivity-tools

## 翻墙工具
Mac下主要使用[ShadowsocksX-NG-R](https://github.com/qinyuhang/ShadowsocksX-NG-R/releases)作为翻墙工具，翻墙源使用[928Net](https://928net.org/)，付费使用，使用了有两年了，网速快+稳定，缺点一个是需要翻墙后才可访问，一个是需要邀请码。

## 终端工具
- [Iterm2](https://github.com/gnachman/iTerm2)：Mac OS X的终端模拟工具，好看+好用
- [OhMyZsh](https://github.com/robbyrussell/oh-my-zsh)：用来美化终端
- [Homebrew](https://brew.sh/index_zh-cn.html)：Mac OS 软件包的管理器

## 编辑器
> 编程专用等宽字体[RobotoMono](https://fonts.google.com/specimen/Roboto+Mono)
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

