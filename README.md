# svg-demos


[1、基本使用](./demo/test1.html)

SVG 文件是一个基于 XML 的 W3C标准，能够跟 W3C 及其他的标准化技术协同工作。SVG 并非仅仅是一种图像格式，它是一种基于 XML 的语言，也意味着它继承了 XML 的跨平台性和可扩展性。

在 HTML 中我们可以理解为一个特殊的 HTML 元素，SVG 有很多特殊属性，其中外观属性也可以像普通 HTML 元素一样通过 CSS 来控制。


[2、做一个 loading](./demo/test2.html)

为什么要用 SVG ？不如举一个最简单，但也最实用的例子。

假如我们需要一个 loading 的图片，这张图片将用在从大到小各种尺寸上，那么图片尺寸太小的话则放大后失真，太大了又占用流量，loading 图标结构很简单，能否像我们用 CSS 设计一个 div 一样设计一张图片，能够放大缩小又不失真？这就是 SVG 能够轻易做到的。

[3、基本形状](./demo/test3.html)

矩形、圆形、椭圆、线条、折线、多边形、路径

[4、path 元素](./demo/test4.html)

<path> 元素/路径可能是SVG中最常见的，也是基本形状中最强大的一个，你可以用path元素绘制矩形（直角矩形或者圆角矩形）、圆形、椭圆、折线形、多边形，以及一些其他的形状，例如贝塞尔曲线、2次曲线等曲线。

参考资料
---------

* [MDN-SVG](https://developer.mozilla.org/zh-CN/docs/Web/SVG)
* [MDN-path](https://developer.mozilla.org/zh-CN/docs/Web/SVG/Tutorial/Paths)
* [W3C标准-SVG](https://www.w3.org/Graphics/SVG/)
