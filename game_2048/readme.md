## 说明
这是一个通过 C 语言实现的 2048 。为了突出游戏的逻辑，界面仅仅使用字符界面进行实现。效果图如下：

（效果图）

## 环境

操作系统：Linux

## 附加依赖项

由于程序使用了 `ncurses` 库来实现绘制管理，所以编译程序之前首先需要安装 `ncurses` 库。

安装方法：

```shell
$ sudo apt-get install libncurses5-dev
```

## 编译

编译的时候需要加上 `-lcurses` 选项。

比如：
```shell
$ gcc game_2048.c -o 2048 -lcurses
```
