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