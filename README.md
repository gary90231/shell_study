# shell_study
The study for shell
The plan for shell

1. 正则表达式
2. 文件和文本处理工具
3. 流程和变量等
4. 大概十几个具体实例



1. 正则表达式
1.1 基本的正则表达式
* ： 用于匹配前面一个字符0次或多次。如 hel*o 可以表示： helo,helllo
. : 匹配任意字符
^ ：匹配行首，如 ^cloud 已cloud 开头的行
$ ：匹配行未, ^$: 空行
[]: 匹配字符集合
\ : 转义符，屏蔽字符特殊含义
\<\> : 精确匹配
\{\} ：字符的重复
2.2 扩展的正则表达式
? : 匹配前面的字符0次或1次
+ : 匹配前面的字符1次或多次
() | ： 可选字符集合

2. 
2.1 sed 
非交互式文本编辑器，对文本文件和标准输入进行编辑





2.2 awk



2.3 sort
文件排序




2.4 uniq
去除文件中重复行



2.5 join
实现两个文件中记录的连续操作



3.1
$(()) 与 $() 还有 ${}
$() 与 ''都表示命令替换
${}: 变量替换

3.2
$@与$*

