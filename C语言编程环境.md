# C语言编程环境

  在linux系统中，许多软件都与windows系统无论是安装包，还是安装方式都有着很大的不同。第一项尝试是使用c语言编程。
  通过百度百科才知道shell命令终端可以实现这个功能（cotrol+alt+t），通过gedit指令打开一个文件，如果这个文件不存在，则会创一个新文件。比如gedit helloworld.c,则会打开(创建并打开)一个名为helloworld的C语言文件。接下来就是正常的c语言的代码写入 。保存过后关闭写代码的界面。继续在shell命令终端输入gcc helloworld.c,则会对文件中的代码编译，显示出错误。最后通过.a/out指令输出指令。

注 :
1：gedit是一个GNOME桌面环境下兼容UTF-8的文本编辑器。它使用GTK+编写而成，因此它十分的简单易用，有良好的语法高亮，对中文支持很好，支持包括gb2312、gbk在内的多种字符编码。gedit是一个自由软件。这是 Linux 下的一个纯文本编辑器,但你也可以把它用来当成是一个集成开发环境 (IDE), 它会根据不同的语言高亮显现关键字和标识符
2:GCC（GNU Compiler Collection，GNU编译器套件），是由 GNU 开发的编程语言编译器。它是以GPL许可证所发行的自由软件，也是 GNU计划的关键部分。GCC原本作为GNU操作系统的官方编译器，现已被大多数类Unix操作系统（如Linux、BSD、Mac OS X等）采纳为标准的编译器，GCC同样适用于微软的Windows。GCC 原名为 GNU C 语言编译器（GNU C Compiler），因为它原本只能处理 C语言。GCC 很快地扩展，变得可处理 C++。后来又扩展能够支持更多编程语言，如Fortran、Pascal、Objective-C、Java、Ada、Go以及各类处理器架构上的汇编语言等，所以改名GNU编译器套件（GNU Compiler Collection）。

