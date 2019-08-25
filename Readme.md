## Introduction

This mpv player plugin is used to blur any area you slected. It is written in lua script.

To install it, just download the file to your mpv scripts folder. (That is `~/.config/mpv/scripts/` on Linux)

该mpv播放器插件用来模糊任意你选定的区域。直接下载该文件到mpv的scripts文件夹即可使用。



You may find it useful to cover the built-in subtitle you don't what to see. For example, watching movies to study another language:

你可以用它来遮挡字幕：

![1566729691288](Readme.assets/1566729691288.jpg)



## Usage

Keyboard button `b` is used toggle it on/off by default. (You can specify another key if you like.)

Press key `b` and click on the first corner. Then move mouse to another corner and click again.

默认使用按键 `b` 进行切换。激活的时候用鼠标点击选区的两个对角即可。

![1566728274407](Readme.assets/1566728274407.jpg)

![1566728299409](Readme.assets/1566728299409.jpg)



> https://superuser.com/questions/901099/ffmpeg-apply-blur-over-face

Crop and lavfi setting codes takes from [here](https://github.com/occivink/mpv-scripts).