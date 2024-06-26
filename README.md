# Moe-Furigana

自用的网易云日文歌词注音插件，仅最低保证可用性

遇到问题了可以反馈，但是我不一定会修，因为本插件是二次开发，不会考虑别人使用的情况

上游分支：[MuttonString/Furigana](https://github.com/MuttonString/Furigana) 现已存档且关闭ISSUE

Version 1.0.3及之前是上游版本的更新日志，修改后的更新从1.0.4开始

事先声明：由于我不会考虑降级回到2.x的网易云，所以这个插件也将只会适配3.x，并且随时做好弃坑的准备

## Moe-Furigana ver.1.0.4

第一个由我接手后的发行版

当前已经能够在我自己的客户端上正常工作

接口需要您自行解决，这需要一个外部接口用于提供注音服务

将来我可能会寻找地方托管它，但是目前不会公开对外使用

## Version 1.0.3

在线API已失效，插件停用

## Version 1.0.2

修复了“汉字修复”功能的少许bug

## Version 1.0.1

因正则表达式不小心多打了一个符号，导致后面跟着括号注音的词语，无法删除标注的振假名。现已修复。请在插件设置页面清除缓存以确保更改能应用

## Version 1.0.0

1. 重写了代码，修复了各种bug
2. 重新制作了设置页面
3. 添加了本地缓存，过期时间为72小时
4. 添加了将简中、繁中特有汉字转换为日标汉字的功能，以提高注音准确度
5. 添加了对“RefinedNowPlaying”插件及配套的“LyricBar”插件的逐字歌词的支持
6. 把更改主歌词字体的功能变为更改日文歌字体，只更改日文歌的字体
7. 技术原因，对“类苹果歌词”插件的逐字歌词不再注音
8. 更改了设置的默认值
9. 更改了设置的保存方式，将不会继承0.x版本的设置

## Version 0.3.0

1. 部分兼容了“类苹果歌词”插件，但bug较多
2. 部分兼容了“RefinedNowPlaying”插件及配套的“LyricBar”插件，但均不兼容逐字歌词
3. 移除了对“Apple Music-like lyrics”插件（即旧版“类苹果歌词”）的兼容
4. 移除了修改罗马音和翻译歌词的字体的功能
5. 移除了将罗马音转换为平假名的功能

## Version 0.2.3

1. 由于功能不完善，移除了根据汉字后面括号内的注音，改变振假名的特性。现后面跟着括号注音的词语，不再标注振假名
2. 修复了缓存已注音歌词的功能失效的问题，同时修复了该功能偶发的只有第一句被注音的问题
3. 潜在问题修复

## Version 0.2.2

1. （测试）将“词”“编”这样的汉字转换为繁体，以便正确注音
2. （测试）将“一人”“二人”这样的词语手动标注为“ひとり”“ふたり”而非机器注音的“いちにん”“ににん”
3. 修复了因代码问题导致的句首汉字注音不准确的问题

## Version 0.2.1

发现插件不再兼容新版Apple Music-like lyrics，即“类苹果歌词”，故在设置界面做出提示。

## Version 0.2.0

1. 由于kuroshiro在线API不可用，将在线API换为kuromoji
2. 对于已经注音过的歌词会进行缓存，以加快再次注音的速度
3. 设置页面的小更改

## Version 0.1.1

测试出Apple Music-like lyrics开启逐词歌词后，使用本插件的部分功能会产生问题。故在设置界面做出提示。

## Version 0.1.0

1. 修复了一些小bug
2. 部分兼容了网易云音乐2.x版本
3. 兼容了Apple Music-like lyrics
