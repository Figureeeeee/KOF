# KOF

## 总览
* 目标：实现一个拳皇demo
* 技术栈：HTML5、CSS3、JavaScript、Git
* ps:JavaScript的一些常用库：jQuery、requestAnimationFrame、canvas

## 按日期写总结

### 2022/11/9：
主要成果：
* 1.实现一个游戏主页面，包含地图以及模拟人物的两个矩形
* 2.通过封装、继承实现了父类`AcGameObject`的子类`GameMap`、`Player`
* 3.利用`requestAnimationFrame`实现父类`AcGameObject`的`update()`函数（以下称为帧函数），实现按帧执行动作，以实现流畅的动画（有点像u3d的生命周期函数hhh）
* 4.在`Player`对象中通过每一帧的时间模拟速度、加速度、位移，并通过帧函数模拟一个状态机（默认情况下为idle状态，根据键鼠输入改变状态，后续可扩展加入触屏按压模式）



待后续完善...