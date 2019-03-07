# Error: ENOENT: no such file or directory, stat ‘C:***demo_book\_book\gitbook\gitbook-plugin-fontsettings\fontsettings.js’

>解决办法：用户目录下找到以下文件。
<user>\.gitbook\versions\3.2.3\lib\output\website\copyPluginAssets.js

Replace all
confirm: true
with
confirm: false
