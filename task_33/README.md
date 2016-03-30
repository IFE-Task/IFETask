# 任务三十三

## 任务描述
 * 实现一个类似棋盘的格子空间，每个格子用两个数字可以定位，一个红正方形的DOM在这个空间内，正方形中的蓝色边表示这是他的正面，有一个input输入框
 * 在输入框中允许输入如下指令，按下按钮后，使得正方形做相应动作
 * GO：向蓝色边所面向的方向前进一格（一格等同于正方形的边长）
 * TUN LEF：向左转（逆时针旋转90度）
 * TUN RIG：向右转（顺时针旋转90度）
 * TUN BAC：向右转（旋转180度）
 * 移动不能超出格子空间
 
## 实现
* 只是任务的第一阶段，存储位移写死了，假如整个表格大小变化，代码缺乏适应性
* 初步调试暂时没发现bug，有bug还请指出
* 代码还是有点渣
* 先这样，代码会每个阶段改进
