![](assets/header.png)

# VerticalFox

在 Firefox 上你也能拥有 Edge 浏览器的自动伸缩垂直标签栏！该主题配合 Sidebery 插件使用，所以收藏夹、标签置顶、独立工作区等功能都一并集成到了侧边栏中，赋予你的 Firefox 一个干净、极简的外观。同时支持 MacOS , Windows 与 Linux。

![](assets/gif1.gif)

# 安装指南

1. 安装 [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) 插件。
2. 根据你所使用的操作系统，下载 release 中的压缩包并解压。（如果你熟悉 Firefox 自定义，你可以直接在源码中找到你要的文件）
3. 在地址栏中输入 `about:config` 并前往，接受风险提示。
4. 搜索 `toolkit.legacyUserProfileCustomizations.stylesheets` 并双击设置为 true。
5. 在地址栏中输入 `about:support` 并前往，在 **应用程序概要** 中找到 **配置文件夹** 并打开。
6. 在打开的目录下新建 `chrome` 文件夹，名称必须全部小写。
7. 复制下载好的 `userChrome.css` 到 `chrome` 文件夹中，重启浏览器。
8. 打开 Sidebery 的设置，前往 **Styles Editor**，在右侧复制粘贴 `sidebery_styles.css` 中的代码。
   ![img](assets/img1.png)

当切换浏览器的亮色/暗色主题时，在 sidebery 设置中也需要进行切换以获得最佳体验：

![](/assets/img2.png)

一切就绪！

## 常见问题

Q： 暗黑模式不起效（或显示不正常）。

A： 设置你的系统主题配色为暗色，然后在 **扩展与主题** 下设置火狐主题为 'auto'。如果仍未解决问题，使用 releases 中 **dark only** 下的文件。

<br/>

Q： 如何将侧边栏移到右边？

A： 在应用 `userChrome.css` 之前，点击侧边栏的顶部栏，会弹出相应选项。如果已经应用了 `userChrome.css`，找到 `/*hide the sidebar header*/` 这句注释，删掉或注释掉位于它和下面 `/*AUTO HIDE SIDEBAR*/` 这句注释之间的代码，侧边栏的顶部栏会显示出来。

<br/>

Q： 怎么关闭侧边栏自动收缩？

A： 找到 `/*AUTO HIDE SIDEBAR*/` 这句注释，删掉接下来的 10 行代码。

