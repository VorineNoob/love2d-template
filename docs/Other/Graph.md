# Other.Graph

图形类，用于在场景中放置图形

受限于 love2d 提供的函数，仅适用于静态图形，因为一旦设置就无法更改坐标了

构造函数内分别填入:

 1. type: 图形的类型，如 "rect", "circle"

 2. mode: 绘制的模式，如 "fill", "line"

 3. rgba: 图形的颜色

 4. draw\_args: 根据每种图形的类型而变

绘制图形时该类会调用:

 1. love.graphics.setColor(rgba)

 2. love.graphics.根据 type 而变(mode, draw\_args)

