# Vi, Java, Ant和Junit的自学报告

## Vi

Vi是在这次实训之前就接触过的工具，在之前主要是在ssh连接服务器的时候需要编辑服务器上的文件时会用到。Vi的使用相较于Sublime Text, VSCode这些在平时可能更常用的工具有着不小的区别，它分为不同的模式，如插入模式，命令模式等，而不是使用鼠标进行选择编辑等操作。在插入模式下输入文本与在普通的编辑器中的效果是一样的， 对于输入的内容会直接插入到编辑的文件，而在命令模式下的操作则是使用各种命令组合进行，比如x是删除单个字符，大写G是调至文档末尾，双击g是跳至文档开头，:wq是保存并退出等等。相对于普通的文本编辑器，Vi毫无疑问是有着更陡峭的学习曲线的，但是熟练使用后也可以提高工作效率，而且通过各种命令可以使对文本的各种编辑操作都不需要通过移动鼠标或者按键盘方向键进行，对于一些人来说可能是一个很大的好处，甚至在使用IDE等工具中也可以安装Vim模式插件来在IDE中获得Vi的编辑体验。若使用Vim(Vi IMproved)的话，相对Vi还可以有更多的模式可使用，而且可以通过配置插件来获得很多的功能，比如补全、更换代码高亮主题等。



## Java

Java语言在实训前仅仅是稍微接触过，但是使用起来熟悉度不高。Java的语法和C++以及C#有不少的相似之处，运行需要先通过javac命令将java文件编译为class文件，再使用java命令用jvm虚拟机运行class文件。