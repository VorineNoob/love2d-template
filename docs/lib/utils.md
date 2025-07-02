# lib.utils

一堆便于编码的函数

## text\_print(text, x, y, size)

使用 font 字体打印文字

参数：

 1. text: 文字

 2. x & y: 文字左上角坐标

 3. size: 字体大小

## text\_printf(text, x, y, max\_width, control, size)

使用 font 字体格式打印文字

参数：

 1. text: 文字

 2. x & y: 文字左上角坐标

 3. max\_width: 详见 love2d 官方文档

 4. control: 格式控制字符串，如 "center"

 5. size: 字体大小

## get\_type(object)

获取某个对象的类型

参数：

 1. object: 对象

## call(func, args)

使用 args 作为参数调用 func

