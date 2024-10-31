# Python外星人侵略项目

本项目来自《Python编程：从入门到实践》第二版，是项目篇的第一个项目。代码是书中三章的集合，是一个完整的可以运行的游戏。但是不包括诸多课后习题的内容。或许由于书籍版本不同会有些许差别。

代码写完之后发现这本书有第三版，我简单看了一下，项目代码没有太大变化，只是加了一个控制游戏帧率的功能，因此本项目代码仍具有参考意义。前面讲python基础语法的部分有一些结构上的变化，更建议按照第三版书籍学习。详细变化参考第三版书中的修订记录。

两版书籍的下载地址：<a href="https://pan.baidu.com/s/1wXJZYXXLUcWr4nU5CzKi9Q?pwd=lvso">百度网盘下载</a>

## 项目结构

AlienAttack文件夹存放代码文件，完全按照书中的结构编写

images文件夹存放游戏素材图片，游戏中需要使用的文件是alien.bmp和ship.bmp,另外的图片是未经处理的原始素材，大小不符合要求。

## 运行游戏

建议先学习书中前几章的内容，了解python的基本语法和一些基本概念。然后一步一步编写代码，出现问题时再对照本程序，有助于快速熟悉语法和面向对象的编程思想。对于环境的安装也可以参考书中的内容。

如果你想快速开始，按照以下步骤进行：

将项目文件夹拷贝到本地，并安装Python环境，本人使用的Python版本为3.12.7，只要别太低应该就行。

在命令行中进入alien_invasion文件夹下，使用`pip install -r requirements.txt`命令安装依赖包。

进入AlienAttack文件夹，运行`python alien_invasion.py`命令即可运行游戏。

<mark>注意</mark>:详细的环境配置请查看<a href="https://github.com/fuyunyou77/alien_invasion/blob/master/python%E5%85%A5%E9%97%A8%E9%A1%B9%E7%9B%AE%E9%85%8D%E7%BD%AE.md">python入门项目配置文件</a>

## 注意事项

1.根据第第二版书籍的设计，游戏中按“q”退出游戏的功能只能在英文输入法下实现，在中文输入法下按“q”无效，第三版不知是否更改。

2.更建议按照第三版的书籍进行学习。
