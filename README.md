> 不再更新，推荐使用 [ct_effect](https://github.com/xingqiao/ct_effect) 的 `brokenglass` 特效

# breakdown
用canvas实现的玻璃破碎效果
支持img和canvas标签

调用方式

1. img.breakdown(TouchEvent/MouseEvent, callback)	// 在touchdown或mousedown事件中调用

2. img.breakdown(x, y, callback)	// 不传x/y值时默认为图片中心点

3. img.initBreakdon(callback)	// 在点击时执行破碎动画，相当于在touchdown事件中执行img.breakdown()

