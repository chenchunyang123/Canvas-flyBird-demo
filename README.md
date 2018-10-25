## 像素鸟游戏说明
* ### 游戏分析
>游戏整体为一只鸟不停地穿越管子，背景不断地后移造成鸟前进的视觉效果，远处的风景移动的速度比近处的地面移动的速度快。
* ### 游戏分类
>整个游戏作为一个大类，然后里面再划分为**鸟类**、**管子类**、**背景类（远处的背景、近处的地面）**、**开始界面类**、**得分类**。
* ### 游戏规则
>鸟自动下落，点击鼠标鸟会向上飞一小段，当鸟碰到管子或者是地面的时候游戏结束（碰撞检测的方案是获取鸟和每根管子的四个顶点，通过判断顶点的位置来确定是否碰撞），得分为坚持的秒数，当坚持**100秒**后，游戏通关。
### demo: [点击我开始起飞](https://chenchunyang123.github.io/Canvas-flyBird-demo/index.html)
