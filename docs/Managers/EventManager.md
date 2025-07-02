# Managers.EventManager

该类用于管理游戏主体的事件

## game\_object

EventManager类中，有一个 game\_object 表

在游戏被启动时，会执行 game\_object 中所有表（对象）的init函数

对于游戏的每一帧，执行 game\_object 中所有表（对象）的update函数，参数填入dt(delay time)，而后执行所有表（对象）的draw函数

## 往 game\_object 中添加对象

调用 EventManager:add\_handle\_object(object) 来添加对象

该函数会检查参数是否为对象，如果是则添加，否则抛出异常结束游戏


