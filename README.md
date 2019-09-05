# ERATranslateHelper
一个用于翻译ERA游戏的翻译工具

Version: Python 3.7.2

Depandencies: tkinter, configparser, js2py


功能：

1、对选择的ERB文件进行处理，提取所有PRINT和DATAFORM行（以下简称行）。

2、通过百度web翻译接口，对选定行进行翻译。

3、格式自动替换，会自动将百分号（如%CALLNAME%）、三项表达式（\@ A? B#C\@）进行替换，避免格式错误。

4、保存翻译好的行，并替换到源文件中，同时保留并注释原文字。

5、支持对所有行进行自动翻译。

6、对选定文件夹内的所有文件转码（从SHIFT-JIS到UTF-8 with BOM）

(2019.4.29)

7、增加了查找、替换翻译内容的功能。

(2019.5.3)

8、增加了关闭时保存确认。

(2019.5.31)

9、修改了全部翻译的功能：新增了时间、开始结束位置等设置项。

(2019.6.29)
10、新增了百度翻译API的翻译模块。

(2019.8.18)
11、生成和读取词典
12、使用可配置的正则表达式进行文件的读取和文本的提取

TODO：
1、用户自定义/设定屏蔽词（自动替换为AAA、BBB等）
2、全文件翻译。
3、原文窗口
可以自定义需要翻译的字符串，使用正则表达式


Total:  35
Total:  17
Exception in Tkinter callback
Traceback (most recent call last):
  File "tkinter\__init__.py", line 1705, in __call__
  File "MainList.py", line 151, in saveButton
  File "Application.py", line 46, in saveFile
  File "ErbFileManager.py", line 102, in saveFile
  File "ErbFileManager.py", line 159, in replaceContent
IndexError: list index out of range
Total:  35
Total:  17