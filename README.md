# PL0-Compiler
### 使用方法

测试PL0代码样例

+ PL0-sourse.txt( 不带read与write命令）
+ PL0-sourse-rw.txt（带read与write命令）

测试方法

+ 在命令行PL0文件夹目录下

  + 编译

    ``` 
    fpc PL0-compiler.pas
    ```

  + 执行

    ```
    PL0-compiler.exe
    ```

  + 输入PL0代码文件（PL0-sourse.txt)

  + 输入结果输出文件（PL0-dest.txt）

+ 最终结果显示在PL0-dest.txt中，包括栈中数据，最终结果，中间代码等

[1](https://github.com/dick20/PL0-Compiler/blob/master/image/1.png)

### 中山大学编译原理项目：PL0语言的编译程序

+ 找到PASCAL编译系统;
+ 在PASCAL系统上运行PL0编译程序,需要对PL0编译程序作一些修改﹑调试;
+ 在PASCAL系统中,为PL0的编译程序建立输入文件和输出文件;
	+ 在输入文件中存放PL0源程序;
	+ 在输出文件中存放PL0源程序被编译后产生的中间代码和运行数据;
+ PL0的编译程序运行时, 通过输入文件输入PL0源程序, 在输出文件中产生源程序的中间代码, 然后运行该中间代码, 在输出文件中产生运行数据;
+ 如果上述工作成功, 则第一项实习任务完成.再做以下工作:
+ 在PL0语言中增加Read和Write语句;
+ 修改PL0编译程序, 使得PL0源程序可以使用Read和Write语句, 从文件(或键盘)输入数据,并可以向文件(或屏幕)写数据.
