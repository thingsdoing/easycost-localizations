Thank you very much willing to add local language translations for EasyCost!

1 Directory Structure Description
Each language has a directory with the rules as "the language abbreviation.proj", such as the English version on en.lproj directory.
A specific translated file named "Localizable.strings", in the language on the directory.

(2) How to add a new language
First,  add a directory for that language.
Copy /en.lproj/localizable.strings file into that directory.
Modify localizable.strings.

3 How to Translate
localizable.strings is a plain text file. You can open and edit with vi, ultroedit, notepad and so on.
Each row corresponds to a translation word, the value of key pairs:
"x" = "y";

x is the key, y is translated content. Quotes and semicolons can not be ignored.
Such as: "世界，你好" = "Hello world";
you can change "Hello world" into the local language, complete the translation.

4 Add comments
/ * This is a comment inside contents * /


-------------------------------------------------------------------------------



非常感谢你愿意为EasyCost添加本地语言翻译！

1. 目录结构说明
每种语言都有一个目录，目录规则为“语言缩写.lproj”，如，英文版本放在en.lproj目录中
具体翻译文件为一个名为Localizable.strings的文件，放在改语言目录下。

2. 如何添加一个新语言
首先，按目录规则添加一个该语言的目录。
将/en.lproj/Localizable.strings 文件复制到该目录中。
修改Localizable.strings。

3. 如何翻译
Localizable.strings 为纯文本文件，用vi,ultroedit,notepad等都可以打开。
每一行对应一个翻译，值键对形式:
"x"="y";   

x为key，y为翻译后内容。引号和分号都不能忽略。
如："世界，你好"="Hello world";
你可以把Hello world换成本地语言，完成翻译。

4. 添加注释
/* 这里面为注释内容 */