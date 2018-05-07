# 对链接应用样式

### 常用的链接选择器

常用的链接选择器有四种，分别为：
*`a:link`
*`a:visited`
*`a:hover`
*`a:focus`
*`a:active
但是需要注意的是当两个规则具有相同的特殊性时，和定义的规则优先，所以最好按照link、visited、hover、foucus、active的次序去应用链接样式。

### 常用的链接样式

* 更改锚的颜色，例如：
```javascript
a {
	color: red;
}
```
* 去掉下划线，例如：
```javascript
a {
	text-decoration: none;
}
```
* 为链接设置背景，例如：
```javascript
a {
	background: url(img/bgcolor.jpg) no-repeat right top;
}
```

