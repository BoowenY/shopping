# Flex布局
inline-flex是行内元素
flex是块级元素，strong也不能同行
flex的xy轴，x变为主轴，y为交叉轴，main，cross
main start作为开始位置，main end作为结束位置
cross start为交叉轴开始位置，cross end作为结束位置
main size主轴大小，cross size交叉轴大小
主轴和交叉轴都是可变的，默认情况下从左至右为主轴，从上至下为交叉轴

flex container主要属性：

flex-flow
flex-direction 决定主轴方向
flex-wrap 换行属性，reverse可以在交叉轴翻转
justify-content   flex-item主轴的对齐方式
align-items   flex-item交叉轴的对齐方式
align-content

flex-basis设置在主轴上的大小，优先级较高
如果没有设置，使用width/height的值，如果都没有，会使用内容的值