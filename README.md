ffmpeg-buid-scripts
===================

====2013-04-08
更新：
armv6未测试
更新build-armv7 armv7s脚本，未更新前出现lipo合并问题。


=====2013-03-30
ffmpeg build for ios scripts armv7s armv7 universal

测试过1.1版本。

下载当前脚本文件
https://github.com/xiangyuan/ffmpeg-buid-scripts.git

下载最新版的FFmpeg库文件（1.1版本测试）
git clone git://source.ffmpeg.org/ffmpeg.git

3。将gas-preprocessor.pl拷贝到/usr/local/bin目录下

5、更改gas-preprocessor.pl的读写权限.(maybe chmod will be used)

4、根据需要将脚本文件拷贝到ffmpeg的根目录下。

如armv7s 将build_armv7s拷贝到ffmpeg目录下

5、执行./build_armv7s执行就可。

感谢这篇文章
http://www.tangentsoftworks.com/blog/2012/11/12/how-to-prepare-your-mac-for-ios-development-with-ffmpeg-libraries/

gas-preprocessor.gl https://github.com/mansr/gas-preprocessor

thanks to @mansr @Tangent Team


