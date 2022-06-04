# HTML杂记
## meta viewport
此元数据常用来适配移动设备。
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no"> 
```
* width=device-width
	将layout viewport（布局视窗）的宽度设置为设备屏幕分辨率的宽度。
* initial-scale=1
	指定页面的初始缩放比例，取1时将layout viewport的宽度设置为屏幕分辨率的宽度的一倍。
* maximum-scale
	指定用户能够放大的最大比例。
* minimum-scale
	指定页面能够缩小的最小比例。
* user-scalable=no
	禁用网页上的浏览器缩放。

## event.preventDefault
如果此事件没有被显式处理，它默认的动作也不应该照常执行。
(尝试用来处理输入不合法不显示)
待续。。。