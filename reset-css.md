### 简单的重置手机端的样式

```css
*,
*:before,
*:after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  -webkit-user-select: none; //禁止用户选中文本
  -webkit-tap-highlight-color: transparent; //移动端系统中点击某标签会触发默认的高亮背景框显示
}
```
