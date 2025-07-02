# Managers.KeyboardEventManager

该类用于管理键盘事件

## check\_events

KeyboardEventManager中，有一个 check\_events 表

其存放 KeyboardEvent 类型的事件

KeyboardEvent:

 1. func: 事件触发时调用的函数

 2. args: 填入 func 的参数

 3. scancode: 调用函数需要按下的键

当键盘被按下时，该类会检查 check\_events 中的事件，如果有匹配的事件则调用相应的函数

## 往 check\_events 中添加对象

调用 KeyboardEventManager:add\_event(func, args, scancode) 来添加一个键盘事件


