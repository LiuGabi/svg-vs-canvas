# SVG 和 Canvas 区别

### SVG
+ 不依赖分辨率
+ 支持事件处理器
+ 最适合带有大型渲染区域的应用程序
+ 复杂度高会减慢渲染速度（任何过度使用 DOM 的应用都不快）
+ 不适合游戏应用

### Canvas
+ 依赖分辨率
+ 不支持事件处理器
+ 弱的文本渲染能力
+ 能够以 .png 或 .jpg 格式保存结果图像
+ 最适合图像密集型的游戏，其中的许多对象会被频繁重绘


