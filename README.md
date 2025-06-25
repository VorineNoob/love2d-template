# README PLZ!!!

如你所见，这是一个由超级大**FW**Lov2d萌新编写的**Love2D**游戏模版，里面包含场景啊场景管理器啊啥啥啥啥的

具体的虽然是我写的但是谁\*\*记得住这么多啊所以说我接下来给佬们介绍一下各个文件

## FILES INTRUDUCTION

### assets/

#### font.ttf

唉这个没啥好讲的就简简单单一个字体文件用于控制字体显示啦因为Love2D要求graphics.printf必须得有字体啊我有什么办法

### lib/

#### utils.lua

装了一堆方便写代码的函数，特别是里面的print和printf特别好用（赞）

> (这个文件名还是我凭感觉写的没想到单词真对了2333)

### .(ROOT DIRECTORY)

#### EventManager.lua

事件管理类

#### GameNameScene.lua

显示游戏名字的场景类

#### GameObject.lua

游戏中的所有对象的公共基类（不包括某些以`Manager`为后缀的类）

#### GameStatusManager.lua

用于管理游戏状态的类

#### LogoScene.lua

在`GameNameScene`场景之前被执行，用于显示工作室的名称

#### Scene.lua

封装了所有场景的共有属性，是所有以`Scene`结尾的单例类的公共基类

#### SceneManager.lua

场景管理器

#### Text.lua

文本类，这个类的每个实例对象都是一个场景中的某个文本

#### Sprite.lua

精灵类，存储图片精灵

#### conf.lua

游戏的配置

#### main.lua

程序的主逻辑（虽然`EventManager`更像）




