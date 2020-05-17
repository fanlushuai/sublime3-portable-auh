# sublime3-portable-auh
这个一个sublime3完美版本(至少我是这么觉得的),**特别推荐** clone本地,直接使用!!!

换机器频繁,或者希望保留配置,之前使用一个sync插件.但是感觉效果不好,**无耻**的利用github.
重新安装sublime3并做了完美的配置,并第一时间传入了此仓库.目的就是大家可以干净的使用.

## README.md 
 **[English](README.en.md)**

## 添加license 
~~网上搜了一个可用的,[github的一个gist,很多人回复,估计日后,失效还能有人提供](https://gist.github.com/cantgis/fb17ab10287c512379fbefad7fa5be1c)~~
这个大家自己上网找吧。容易gg,也容易找。
## 添加package control.
大多数人使用sublime都止步于此,所以无法感知sublime的强大;[package control安装方式](https://packagecontrol.io/installation)

## 添加优秀插件
- Pretty JSON: json格式化
- HostsEdit:快速打开hosts文件
- SqlBeautifier: sql格式化
- Compare Side-By-Side: 对比文件
- ConvertToUTF8:一些编码问题
- Trimmer:移除空行,等操作(如果没有此插件,大家做法都是写正则替换.显然,每次都写不方便)
- Colorsublime: 配色库,可以挑选大量配色.
- Theme-Soda: soda的主题,排行靠前.我也觉得挺好.
- Keymaps: 快捷键提示的.插件安装的太多,一时间忘记快捷键很正常,有了它再也忘不了了.(插件配合快件键使用才是最舒服的!!!)
- SublimeLinter: 语法检查
- InsertNums: 在列模式下，插入顺序数字

说明: 新版本的 package control提供批量安装插件.如果不想使用本项目的,可以批量搞一下.
Pretty JSON ,HostsEdit ,SqlBeautifier ,Compare Side-By-Side ,ConvertToUTF8 ,Trimmer ,Colorsublime ,Theme-Soda ,Keymaps ,SublimeLinter

## 做了喜好设置.
- 光标加粗: "wide_caret": true
- 主题选择: "theme": "Soda Light 3.sublime-theme"
- 配色选择: 使用colorsublime选择的一款 "color_scheme": "Packages/Colorsublime - Themes/Tomorrow_Night_Eighties.tmTheme"
- 在menu->view->hide-minimap (个人是快捷键患者,所以认为外观尽量简洁)
- 在menu->view->hide-menu,menu不常用,可以通过alt键,直接显示. (个人是快捷键患者,所以认为外观尽量简洁)

## 如何感受sublime的强大,平常如何用?(老手绕过)
1. 熟练掌握[快捷键](https://www.shortcutfoo.com/app/dojos/sublime-text-3-win/cheatsheet)
基础的快捷键就不说了.以下3个感觉很不错:
-    ctrl+d选中相似位置  很高级
-    ctrl+shift+上下方向键  列模式
-    ctrl+shift+L 列模式的全选中的方式
-    ctrl+j 一行所有
2. 复杂编辑引入正则,把正则使用在查找和替换上,你会觉得操作非常快捷而炫酷,还能练习正则.[正则语法](https://github.com/ziishaned/learn-regex/blob/master/translations/README-cn.md)
3. 遨游插件海洋. 没事可以去 **[插件仓库](https://packagecontrol.io/)** 看看,有哪些排名靠前的,优秀的都可以用用.还有一些功能,你觉得应该有插件的,都可以搜索一下.

## 绿色版本的文件关联问题
建议windows用户自己学习一下注册表相关知识,下面提供一个别人写好的注册表修改脚本

[Sublime-Text-Portable-Tool.bat](https://github.com/loo2k/Sublime-Text-Portable-Tool/blob/master/Sublime-Text-Portable-Tool.bat)
