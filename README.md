# randomcolor
一个小trick，设置区域的随机颜色。
使用的核心语句：
```js
Math.floor(Math.random()*(2<<23)).toString(16);
```
