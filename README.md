##包含项目简介、使用方式、相关链接##


.editorconfig : 用于统一代码工具解决方案，在不同编辑器统一代码风格，告诉编译器缩进.gitignore : 管理源代码，告诉git版本工具哪些文件不需要版本管理

1.创建LICENSE.txt（大写是因为约定俗成的）：里边包含着版权声明，或是协议内容； 2.创建REASME.md文件：包含项目简介、使用方式、相关链接； 3.CHANGLOG.md：包含每个版本的更新；说明版本号、更新内容、修复了哪些问题等；

渐进增强和优雅降级 渐进增强 progressive enhancement ：先简单效果，再根据不同浏览器不同分辨率逐渐追加效果 优雅降级 greceful degradation ：先做到优雅的效果，在根据不同浏览器不同分辩率逐渐减少效果。 优雅降级更好 针对用户体验来说 思想是让老浏览器可以用，新的浏览器体验更好

各浏览器终端同步测试：www.browsersync.cn 使用npm安装：npm install -g browser-sync 启动：browser-sync start --server "src" --files "src"

1.建立404页面（4.4.html）:找不到正确页面，跳转到的页面；替换服务器上默认的错误页页面； 2.创建robots.txt文件（机器人：给机器看的，给搜索引擎看的）：是搜索引擎访问网站时查看的第一个文件，这个文件告诉引擎什么能查看，什么不能查看； 3.创建favicon.ico文件：网站的logo，在网站的标签上显示； 4.创建humans.txt文件（人类：给人看的）：保存网站建设者和一些其他的有用的信息

#http-server是一个简单的，零配置的命令行http服务器。#
##全局安装：npm install http-server -g##
1. 先进入项目目录
2. 输入命令http-server [执行文件的路径]，如http-server src

多设备多浏览器同步测试工具：BrowserSync
1. 全局安装：npm install -g browser-sync
2. 先进入项目目录
3. 启动 BrowserSync browser-sync start --server src --files src


