# HTML的引入
## HTML的概念
1. HTML 是用来描述网页的一种语言。
2. HTML 指的是超文本标记语言: HyperText Markup Language
3. HTML 不是一种编程语言，而是一种标记语言
4. 标记语言是一套标记标签 (markup tag)
5. HTML 使用标记标签来描述网页
6. HTML 文档包含了HTML 标签及文本内容
7. HTML文档也叫做 web 页面

## HTML 标签(- HTML 标记标签通常被称为 HTML 标签 (HTML tag))
1. HTML 标签是由尖括号包围的关键词，比如 <html>
2. HTML 标签通常是成对出现的，比如 <b> 和 </b>
3. 标签对中的第一个标签是开始标签，第二个标签是结束标签
4. 开始和结束标签也被称为开放标签和闭合标签
- eg：<标签>内容</标签>

## HTML 元素
"HTML 标签" 和 "HTML 元素" 通常都是描述同样的意思.
一个 HTML 元素包含了开始标签与结束标签

## Web 浏览器
Web浏览器（如谷歌浏览器，Internet Explorer，Firefox，Safari）是用于读取HTML文件，并将其作为网页显示。
浏览器并不是直接显示的HTML标签，但可以使用标签来决定如何展现HTML页面的内容给用户

## HTML 网页结构
下面是一个可视化的HTML页面结构：<img width="1462" height="764" alt="daccdb407eaba6981281ecc1419347b0" src="https://github.com/user-attachments/assets/75769ef6-7fd6-4eb6-8cca-bcf7a867c72a" />

## <!DOCTYPE> 声明
<!DOCTYPE>声明有助于浏览器中正确显示网页。
网络上有很多不同的文件，如果能够正确声明HTML的版本，浏览器就能正确显示网页内容。
doctype 声明是不区分大小写的，以下方式均可：
```html
<!DOCTYPE html>
<!DOCTYPE HTML>
<!doctype html>
<!Doctype Html>
```

## 中文编码
- 目前在大部分浏览器中，直接输出中文会出现中文乱码的情况，这时候我们就需要在头部将字符声明为 UTF-8 或 GBK。
- 只有body部分能显示出来
```html
HTML 实例
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>
页面标题</title>
</head>
<body>
<h1>我的第一个标题</h1>
<p>我的第一个段落。</p>
</body>
</html>
```
## 通用声明
HTML5
<!DOCTYPE html>
HTML 4.01
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
XHTML 1.0
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">

## 如何使用 VS Code 工具来创建 HTML 文件
1. 新建 HTML 文件，如图<img width="527" height="316" alt="EAD13C0B-0BE9-411E-8E2A-23600B0BEF9B" src="https://github.com/user-attachments/assets/6edd04d6-14f6-43a3-a1f0-0383f19f4700" />
2. 另存为 HTML 文件，然后选择" 文件(F)->另存为(A) "，文件名为 runoob.html
3. 在浏览器中运行这个 HTML 文件，然后鼠标右击编辑器上的文件名，选择在默认浏览器打开（也可以其他的浏览器）
- 注：vscode 中使用浏览器打开 html 文件需要 安装 "open in browser" 扩展。
5. VS Code 可以安装 Live Preview 插件来实时预览编写的代码（在编辑窗口右击鼠标，选择 Show Preview 选项）

# HTML基础
## HTML 标题
HTML 标题（Heading）是通过```<h1> - <h6> ```标签来定义的。
实例
```html
<h1>这是一个标题</h1>
<h2>这是一个标题</h2>
<h3>这是一个标题</h3>
```
## HTML 段落
```html
HTML 段落是通过标签 <p> 来定义的。
实例
<p>这是一个段落。</p>
<p>这是另外一个段落。</p>
```
## HTML 链接
```html
HTML 链接是通过标签 <a> 来定义的。
实例
<a href="https://www.runoob.com">这是一个链接</a>
```
## HTML 图像
```html
HTML 图像是通过标签 <img> 来定义的.
实例
<img src="/images/logo.png" width="258" height="39" />
```
注意： 图像的名称和尺寸是以属性的形式提供的。

# HTML元素
HTML 文档由一系列 HTML 元素（Element）构成，是网页结构的基础。

## 什么是 HTML 元素？
HTML 元素是从开始标签（start tag）到结束标签（end tag）之间的完整结构。
<img width="644" height="128" alt="904906c7c565db93fe589194a574a3d8" src="https://github.com/user-attachments/assets/7fed1eac-2fb6-4423-802e-5bc9b1477ead" />

开始标签也称为 起始标签（opening tag）
结束标签也称为 闭合标签（closing tag）

## HTML 元素语法规则
1. 元素以开始标签开始，以结束标签结束
2. 元素内容位于开始标签与结束标签之间
3. 部分元素为**空元素**（empty element），没有内容
4. 空元素通常在开始标签中自闭合（如 <br />）
5. 大多数元素可以包含**属性**（Attributes）

## HTML 元素的嵌套
HTML 元素可以相互嵌套，形成树状结构：
一个元素可以包含其他元素
HTML 文档本质上是一个嵌套结构（DOM 树）

## HTML 文档示例
```html
<!DOCTYPE html>
<html>

  <body>
    <p>这是第一个段落。</p>
  </body>

</html>
```
该示例包含 3 个核心元素：html、body、p。
