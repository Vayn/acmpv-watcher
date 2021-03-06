# AcmpvWatcher

__[acmpv](https://github.com/Vayn/acmpv) + watcher__

监控剪贴板自动调用 acmpv 播放 Acfun & Bilibili 及[其他网站视频](https://github.com/soimort/you-get#supported-sites)

## 安装

### 必要条件

* [acmpv](https://github.com/Vayn/acmpv)

### 安装方法

1) 下载 AcmpvWatcher 的 dmg 安装包；

2) 打开安装包，将 AcmpvWatcher 应用拖入 `/Applications` 目录即可。

运行后在菜单栏出现一个小星星就是 __AcmpvWatcher__

![screenshot](screenshot.gif)

## 使用

1、复制 Acfun, Bilibli 或其他视频网站的视频网址

2、拖拽视频链接至 AcmpvWatcher 菜单栏图标

以上方式可使 AcmpvWatcher 自动调用 acmpv 播放视频

### 全局热键

<kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>x</kbd> 同时按下 `command` + `option` + `x` 可打开或暂停监控功能

### 注意事项

1. 受 [You-Get](https://github.com/soimort/you-get) 本身所限，只能播放 Bilibili 的普通视频，不能播放番剧


### Changelog

* 12.11.2016 v1.3.0: 使用 HUD 方式通知监控状态
* 11.27.2016 v1.2.0: 加入全局热键设置
* 10.25.2016 v1.1.0: 改善应用卡顿问题
* 10.24.2016 v1.0.5: 加入自动更新功能，修复拖拽导致启动两次 mpv 情况。
