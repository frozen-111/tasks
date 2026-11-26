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
一个 HTML 元素包含了开始标签与结束标签，如下实例:
HTML 元素:
<p>这是一个段落。</p>

## Web 浏览器
Web浏览器（如谷歌浏览器，Internet Explorer，Firefox，Safari）是用于读取HTML文件，并将其作为网页显示。
浏览器并不是直接显示的HTML标签，但可以使用标签来决定如何展现HTML页面的内容给用户

## HTML 网页结构
下面是一个可视化的HTML页面结构：<img width="1462" height="764" alt="daccdb407eaba6981281ecc1419347b0" src="https://github.com/user-attachments/assets/75769ef6-7fd6-4eb6-8cca-bcf7a867c72a" />

## <!DOCTYPE> 声明
<!DOCTYPE>声明有助于浏览器中正确显示网页。
网络上有很多不同的文件，如果能够正确声明HTML的版本，浏览器就能正确显示网页内容。
doctype 声明是不区分大小写的，以下方式均可：
- <!DOCTYPE html>
- <!DOCTYPE HTML>
- <!doctype html>
- <!Doctype Html>

## 中文编码
- 目前在大部分浏览器中，直接输出中文会出现中文乱码的情况，这时候我们就需要在头部将字符声明为 UTF-8 或 GBK。
- 只有body部分能显示出来
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

## 通用声明
HTML5
<!DOCTYPE html>
HTML 4.01
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
XHTML 1.0
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">

