# lib.Timer

计时回调，每隔一段时间调用一个函数

## intervals

存储回调方案

## interval\_call(func, args, delay\_second, dt)

用于创建一个回调方案

参数：

 1. func: 函数

 2. args: 填入 func 的参数

 3. delay\_second: 每次调用之间间隔的秒数

 4. dt: 填入 delay time

## enable(func)

用于启用一个回调方案

参数：

 1. func: 函数

## disable(func)

用于关闭一个回调方案

参数：

 1. func: 函数

