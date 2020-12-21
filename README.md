# Canvas
canvas学习:

<canvas> 是 HTML5 新增的元素，可用于通过使用 JavaScript 中的脚本来绘制图形。例如，
<canvas> 标签允许脚本语言动态渲染位图像。<canvas> 标签创建出了一个可绘制区域，JavaScript 代码可以通过一套完整的绘图功能类似于其他通用二维的 API 访问该区域，从而生成动态的图形。我们可以认为 <canvas> 标签只是一个矩形的画布。JavaScript 就是画笔，负责在画布上画画。

什么是 Canvas？Canvas 是为了解决 Web 页面中只能显示静态图片这个问题而提出的，一个可以使用 JavaScript 等脚本语言向其中绘制图像的 HTML 标签。


## 绘制路径
<!-- PS 中的路径是矢量的，而 Canvas 中的路径不是 -->
fill() 填充路径
stroke() 描边
arc() 创建圆弧
rect() 创建矩形
fillRect() 绘制矩形路径区域
strokeRect() 绘制矩形路径描边
clearRect() 在给定的矩形内清除指定的像素
arcTo() 创建两切线之间的弧/曲线
beginPath() 起始一条路径，或重置当前路径
moveTo() 把路径移动到画布中的指定点，不创建线条
lineTo() 添加一个新点，然后在画布中创建从该点到最后指定点的线条
closePath() 创建从当前点回到起始点的路径
clip() 从原始画布剪切任意形状和尺寸的区域
quadraticCurveTo() 创建二次方贝塞尔曲线
bezierCurveTo() 创建三次方贝塞尔曲线
isPointInPath() 如果指定的点位于当前路径中，则返回 true，否则返回 false
