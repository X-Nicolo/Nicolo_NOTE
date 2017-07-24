# eeclipse的安装和使用
1. 安装luna版本
2. 新建一个项目。
File->New->Java Project,命名位Hello World.
在src下New-Class.可选是否创建主函数。

### 第一次运行，右键Run as->Java Apllication.此后即可使用工具栏的run按钮。
快捷键:trl+F11
src:srouce code
在src下正规的创建包，遵循MVC结构.

cf.xiaosablog.hello.main   控制的代码
cf.xiaosablog.hello.model   模型
cf.xiaosablog.hello.view    视图

### 创建包的操作：src右键->New->Java Package

然后在Main包里创建主方法。
New->class->勾选public static void main(String[] argss)

在model里创建储存数据模型。
在View创建用户界面和视图。

### 问题:
在eclipse里syso无法补全。
### 解决：
在Windows->preference->java-content assist->Auto->activation trrggers for java:输入键盘上的26个字母及符号即可。

### try catch:
右键surround with->try catch.
在catch里，syse:System.err.println();
将错误输出。

### 断点调试：
双击该行。 点击上边的debug按钮。

### 快捷按键：
Ctrl+1：快捷修复。
Ctrl+D:快捷删除行。
Shift+enter：在下一行创建新的行。
tab:一步缩进。
Ctrl+F11：快捷运行。
Alt+上/下：快速移动行。
Ctrl+Alt+上/下：快速复制行。
Ctrl+M：将当前窗口放大。
Alt+/:快速补全。
Ctrl+/:注释。







