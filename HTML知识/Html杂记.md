# HTML杂记
## meta viewport
此元数据常用来适配移动设备，width属性被用来控制layout viewport（布局视窗）的宽度。
```html
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1"> 
```
* width=device-width
	将layout viewport（布局视窗）的宽度设置为设备屏幕分辨率的宽度。
* initial-scale=1
	指定页面的初始缩放比例，取1时将layout viewport的宽度设置为屏幕分辨率的宽度的一倍。
* maximum-scale
	指定用户能够放大的最大比例。
* minimum-scale
	指定页面能够缩小的最小比例。
