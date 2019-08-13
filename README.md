Listen 1
==========

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)
[![platform](https://img.shields.io/badge/python-2.7-green.svg)]()

Listen 1 让你用一个网页就能听到多个网站的在线音乐（现已包括网易云音乐，QQ音乐，虾米音乐，豆瓣音乐）。你可以非常的简单的访问和收听在线音乐，而不用受到单个音乐网站资源不全的限制了。

它不仅能搜索多家在线音乐提供商的资源，还能方便的整理你喜欢的音乐，制作自己的歌单。尽兴的享受音乐吧！

支持浏览器：IE 11, Chrome, FireFox, Safari

* 主页：国内请访问[http://githublisten1.coding.me/listen1/](http://githublisten1.coding.me/listen1/)
* 联系邮箱：githublisten1@gmail.com

[![platform](http://i.imgur.com/if4CNr2.png?1)]()


安装
----
Chrome插件版

    下载Chrome插件版压缩包，并解压缩
    打开 Chrome 扩展页面，勾选右上角「开发者模式」
    选择「加载已解压的扩展程序…」，选择刚刚解压缩的文件夹
    开始使用

Firefox插件版

    下载Firefox插件版，并解压缩
    打开 about:config 页面，xpinstall.signatures.required 设置为 false
    选择「附加组件」，齿轮图标，选择从文件安装附加组件，选择下载的xpi文件
    开始使用

Windows桌面版

    下载Windows压缩包，根据系统选择32位或64位版本
    解压缩，运行 Listen1.exe

Mac桌面版

    下载并运行dmg，在打开的安装窗口把Listen 1图标拖动到右侧
    点击Listen 1图标运行

Linux桌面版

    根据系统选择32位或64位版本，下载AppImage安装包
    将安装包放到合适的位置，右键安装包>属性>权限>赋予执行权限，或在命令行使用chmod a+x赋予执行权限，然后就可直接双击运行软件，弹出是否将软件集成到程序菜单中的窗口，同意或不同意都可运行软件，建议同意
    如果需要debian安装包，请访问 此链接


调试开发
----------
后台基于tornado开发，可以用Python环境直接运行。

1. pip环境下安装在requirements下的package

	pip install -r requirements/dev.txt

2. python app.py
3. 访问 http://localhost:8888/

打包
----
打包注意事项请参考[readme_mac.md](https://github.com/listen1/listen1/blob/master/readme_mac.md)和[readme_windows.md](https://github.com/listen1/listen1/blob/master/readme_windows.md)。

致谢
----
在开发过程中，参考了很多音乐网站API的分析代码和文章，感谢这些开发者的努力。（具体项目网址参考源码）


License
--------
MIT
