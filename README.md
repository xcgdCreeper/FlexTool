##欢迎使用xcgdCreeper写的flex辅助小工具v0.5
###本工具集成了tcc编译器和flex,可以自动生成.l文件和lex.yy.c并编译

##使用说明

*在in文本框中输入要判断的文法

*点击生成按钮，通过flex生成.l和对应的c源文件

*若显示failed，检查.l文件的语法并点击生成按钮，直到显示success

*若显示success,说明成功生成，点击执行按钮开始分析

*分析结果显示在out文本框中

##文件夹中的内容

*FlexTool.exe:运行本工具

*lex.l:.l文件，通过.l文件的规则，生成c语言源文件

*in.txt:输入符号串(显示在文本框中，无需手动编辑)

*out.txt:输出token表(显示在文本框中，无需手动编辑)

*lex.yy.c,lex.yy.exe:自动生成的文件,若显示failed说明文件没有成功生成，需要检查.l文件的语法
