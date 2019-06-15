# dnSpy

dnSpy是一个调试器和. net汇编编辑器。即使没有可用的源代码，也可以使用它来编辑和调试程序集。
想说谢谢吗?点击页面顶部的星星。或者叉dnSpy和发送PR!
以下图片显示dnSpy正在行动。它显示了dnSpy编辑和调试. net EXE文件，而不是源代码。

![debug-animated](images/debug-animated.gif)

![edit-code-animated](images/edit-code-animated.gif)

# Features (see below for more detail)

调试。net框架，。net核心和Unity游戏程序集，不需要源代码
-编辑c#或Visual Basic或IL中的程序集，并编辑所有元数据
-明暗主题
-可扩展，编写自己的扩展
-高DPI支持(支持每个监视器的DPI)
-更多，见下文
dnSpy使用ILSpy反编译引擎和Roslyn (c# / Visual Basic)编译器以及许多其他开源库，更多信息请参见下面。

# Binaries

[Latest release](https://github.com/0xd4d/dnSpy/releases) (Note: Required .NET Runtime version is [.NET Framework 4.7.2](https://dotnet.microsoft.com/download/thank-you/net472))

Latest build: [![Build status](https://ci.appveyor.com/api/projects/status/3utl4e1qkx7pamko/branch/master?svg=true)](https://ci.appveyor.com/project/0xd4d/dnspy/branch/master/artifacts)

Or build it from source, see the [Wiki](https://github.com/0xd4d/dnSpy/wiki/Building-dnSpy).

# Debugger

调试。net框架，。net核心和Unity游戏程序集，不需要源代码
-设置断点并进入任何程序集
-本地，手表，汽车窗口
windows支持保存变量。
解密字节数组)到磁盘或在十六进制编辑器(内存窗口)中查看它们
- - - - - -对象id
-可以同时调试多个进程
-模块加载时断开
-跟踪点和条件断点
-导出/导入断点和跟踪点
调用堆栈，线程，模块，进程窗口
-抛出异常时中断(第一次机会)
-变量windows支持计算c# / Visual Basic表达式
-可以调试动态模块(但由于CLR的限制，不能调试动态方法)
- Output窗口记录各种调试事件，默认情况下显示时间戳:)
-程序集解密自己在运行时可以调试，dnSpy将使用内存中的映像。
您还可以强制dnSpy始终使用内存映像而不是磁盘文件。
-公共API，你可以写一个扩展或使用c#交互窗口来控制调试器

# Assembly Editor

- All metadata can be edited
- Edit methods and classes in C# or Visual Basic with IntelliSense, no source code required
- Add new methods, classes or members in C# or Visual Basic
- IL editor for low level IL method body editing
- Low level metadata tables can be edited. This uses the hex editor internally.

# Hex Editor

-所有元数据都可以编辑
-编辑方法和类在c#或Visual Basic与智能感知，不需要源代码
-在c#或Visual Basic中添加新方法、类或成员
- IL编辑器，用于低水平的IL方法体编辑
-可编辑低层元数据表。这在内部使用十六进制编辑器。

# Other

——BAML解码器
-蓝色、浅色和深色主题(以及深色高对比度主题)
——书签
c#交互式窗口可以用来编写dnSpy脚本
-搜索程序集的类，方法，字符串等
-分析类和方法的使用情况，寻找调用者等
-多个标签和标签组
-引用被突出显示，使用Tab / Shift+Tab移动到下一个引用
-进入进入点和模块初始化命令
-转到元数据令牌或元数据行命令
-代码工具提示(c#和Visual Basic)
-出口至项目

# List of other open source libraries used by dnSpy

- ILSpy decompiler engine (C# and Visual Basic decompilers)
- Roslyn (C# and Visual Basic compilers)
- dnlib (.NET metadata reader/writer which can also read obfuscated assemblies)
- VS MEF (Faster MEF equals faster startup)
- ClrMD (Access to lower level debugging info not provided by the CorDebug API)

# Translating dnSpy

[Click here](https://crowdin.com/project/dnspy) if you want to help with translating dnSpy to your native language.

# Wiki

See the [Wiki](https://github.com/0xd4d/dnSpy/wiki) for build instructions and other documentation.

# License

dnSpy is licensed under [GPLv3](dnSpy/dnSpy/LicenseInfo/GPLv3.txt).

# [Credits](dnSpy/dnSpy/LicenseInfo/CREDITS.txt)
