# python-package
python常用的一些类包汇总说明,都是基于python3写的或者直引用的一些官方demo,pip3安装我用的是淘宝的源,争取每日更新一个吧^_^

## Python标准库

### logging
[example](./example/logging/)

Python标准库，日志文件生成管理函数库。[logbook](https://github.com/getlogbook/logbook) logging的替换品,有兴趣的可以自己看看。
级别排序:CRITICAL > ERROR > WARNING > INFO > DEBUG

## 数据库

### [pymysql 链接mysql的库](https://github.com/PyMySQL/PyMySQL)
[example](./example/pymysql/)

pymysql是在 Python3.x 版本中用于连接 MySQL 服务器的一个库，Python2中则使用mysqldb。

## web框架

## 爬虫

## 图像处理

### [Tesseract OCR光学字符识别](https://github.com/madmaze/pytesseract)
[example](./example/tesseract/)

python的光学字符识别（OCR）工具，识别并“读取”图像中嵌入的文本，是Google Tesseract-OCR Engine的包装。可以用作tesseract的独立调用脚本，可以读取Pillow和Leptonica图像库支持的所有图像类型，包括jpeg，png，gif，bmp，tiff等。此外，打印和识别的文本，而不是将其写入文件。

## 机器学习