CKReader-WP8
============

Windows Phone 8版读书软件，已实现打开邮件附件和从SD卡读取书籍，未来会支持书朋网和SkyDrive

目前的水平：

1. 只支持WP8
2. 能从SD卡的\Books目录下读取所有的.txtx后缀的纯文本书（绑定txt的尝试失败了），只支持UTF8编码
3. 用了一个第三方的无限长文本控件，翻页时渲染一次非常慢，但是渲染完之后滑动是正常的
4. 支持全角括号包半角数字作为章节号，以此自动分章节，由于上面说的那个控件本身的问题，不分章节的书可能看不了
5. 界面巨烂，只实现了选文件、看书、翻页、改字号，其他功能都没有……
6. 有些崩溃问题没能解决，打开文件和改字号有小概率会崩溃

Windows Phone Store下载地址
------------
http://www.windowsphone.com/en-us/store/app/ckreader/088a5ae5-f58e-4390-9d79-63b32f1b8688

Windows Phone Store更新日志
------------
**v1.0.2(2013-4-7)**
增加了打开邮件附件的功能
重新绘制了图标和磁贴图片，更符合平台统一风格
界面切换加入动画效果

欢迎使用CKReader文本阅读工具，本工具支持所有以.txtx为后缀名的UTF-8编码纯文本文件。要在应用启动时的文件列表中看到您的书籍，请将下载的书籍文件改名为.txtx后缀，放在手机的SD卡根目录，或者是SD卡的Book/Books文件夹下，再运行本应用。

TODO list
------------
1. 支持背景图片 
2. 字体和阅读进度自动保存 
3. 对接书朋网API下载txt书籍
4. 移植到WP7（短期没时间实现）
