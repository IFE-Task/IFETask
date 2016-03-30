# 任务十七

## 任务描述
 * 参考以下示例代码，原始数据包含几个城市的空气质量指数数据
 * 用户可以选择查看不同的时间粒度，以选择要查看的空气质量指数是以天为粒度还是以周或月为粒度
 * 天：显示每天的空气质量指数
 * 周：以自然周（周一到周日）为粒度，统计一周7天的平均数为这一周的空气质量数值，如果数据中缺少一      个自然周的几天，则按剩余天进行计算
* 月：以自然月为粒度，统一一个月所有天的平均数为这一个月的空气质量数值
* 用户可以通过select切换城市
* 通过在"aqi-chart-wrap"里添加DOM，来模拟一个柱状图图表，横轴是时间，纵轴是空气质量指数，参考图（点击打开）。天、周、月的数据只根据用户的选择显示一种。
* 天：每天的数据是一个很细的矩形
* 周：每周的数据是一个矩形
* 月：每周的数据是一个很粗的矩形
* 鼠标移动到柱状图的某个柱子时，用title属性提示这个柱子的具体日期和数据
 
### 式例代码就不粘了	
## 实现
* 还没借鉴别人怎么写的，先自己写一套，学习了别人的再改进
* 图表想法是用flex来模仿，考虑比较简单，效果也不怎么好，而且flex兼容性只能兼容ie8以上
* 添加y轴坐标作为数据参考
* 部分代码比较冗余，数据处理还有点渣，还要多练
* 每周直接统计的7天，考虑得有点简单，没考虑每日对应星期几
* html部分没怎么美化，有点丑，将就看了!- -
