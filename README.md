### JavaScript30 - 一个月纯 JS 挑战中文指南

 跟着此开源项目每天做一个练习

#### TODO

- [ ] 19 摄像头调用
- [ ] 20 麦克风语音输入
- [ ] 21 罗盘测试
- [ ] 23 语音合成

#### 新接触的知识点

1. transitionend 事件

transitionend 事件会在 CSS transition 结束后触发. 当transition完成前移除transition时，比如移除css的transition-property 属性，事件将不会被触发.如在transition完成前设置  display 为"none"，事件同样不会被触发。

2. getBoundingClientRect

[api地址](https://developer.mozilla.org/zh-CN/docs/Web/API/Element/getBoundingClientRect)

Element.getBoundingClientRect()方法返回元素的大小及其相对于视口的位置。

3. addEventListener的第三个参数
网景 和 微软 曾经的战争还是比较火热的，当时， 网景主张捕获方式，微软主张冒泡方式。后来 w3c 采用折中的方式，平息了战火，制定了统一的标准——先捕获再冒泡。
addEventListener的第三个参数就是为冒泡和捕获准备的.
addEventListener有三个参数：

> element.addEventListener(event, function, useCapture)

第一个参数是需要绑定的事件
第二个参数是触发事件后要执行的函数
第三个参数默认值是false，表示在事件冒泡阶段调用事件处理函数;如果参数为true，则表示在事件捕获阶段调用处理函数。