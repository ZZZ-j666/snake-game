# C++ 控制台贪吃蛇小游戏
基于 Windows API + conio.h 实现的控制台贪吃蛇

## 操作方式
- W：向上
- S：向下
- A：向左
- D：向右

## 功能
- 边界碰撞死亡
- 撞到自身死亡
- 随机生成食物
- 吃到食物蛇身变长
- 控制转向防反向直接撞死

## 编译运行
环境：MinGW g++
```bash
g++ main.cpp -o main.exe
.\main.exe
