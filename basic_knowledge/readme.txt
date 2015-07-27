采用BrowserSync 这样的好处是，编写边测试
1.先去安装browserSync
   npm install browser-sync --save-dev
2. 启动BrowserSync
browser-sync start --server --files "**/*.css, **/*.html"
=========================================
*绘制canvas是有顺序的

绘制方块：
·fillRect(x,y,w,h)  默认颜色是黑色
·strokeRect(x,y,w,h); 带边框的方块
=========================================
设置样式：
.fillStyle='red'  填充颜色 
.lineWidth	线宽
.strokeStyle   描边的颜色
=========================================
边界点的样式：
·lineJoin: 边界连接点的样式
	miter (默认) | round(圆角) | bevel(斜角)

.lineCap: 端点样式  暂时测试无效果
	butt(默认)  | round(圆角) | square(高度多出为宽一半的值)

=========================================
绘制路径
beginPath : 开始绘制路径
closePath : 结束绘制路径
moveTo : 移动到绘制的新目标点
lineTo : 新的目标点
stroke : 划线，默认黑色
fill : 填充，默认黑色
rect : 矩形区域
clearRect : 删除一个画布的矩形区域
save : 保存路径
restore : 恢复路径
=========================================
绘制圆形：
	arc(x,y,r,起始弧度，结束弧度，旋转方向)

弧度与角度的关系：
	弧度=角度*Math.PI/180
		

