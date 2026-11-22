# Markdown 学习笔记
Markdown 是轻量级标记语言，语法简单，专门用来写文档，GitHub 的 README 就是用它写的。（**注意空格，换行均会影响效果，打完预览里进行检查**）
 - 学习参考：[请叫我AXin快速掌握markdown](https://b23.tv/9fE9NUE)
 - [毛怪的学习日记markdown入门使用教学](https://b23.tv/5flCWcc)

## 基本概念
Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。使用Markdown 编写的文档可以轻松地导出为 HTML、Word、图像、PDF、Epub 等多种格式的文档。当前许多网站都支持使用 Markdown 来撰写文档或者发表文章。例如：GitHub、简书、StackOverflow、有道云笔记等等。

## 一、标题
一共六级，# 的数量代表级别
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 二、文本样式
**加粗**

*斜体*

***加粗斜体***

~~删除线~~

<u>下划线</u>

## 三、列表
- 无序列表第一条
- 无序列表第二条
  - 子列表

1. 有序列表第一条
2. 有序列表第二条

## 四、表格
| 名称 | 作用 |
| ---- | ---- |
| push | 推送 |
| pull | 拉取 |

## 五、任务清单
- [x] 已经完成
- [ ] 待完成

## 六、引用
> 引用一段文字

## 七、代码
行内代码`printf("hello");`

代码块，支持标注语言
```c
#include <stdio.h>
int main()
{
    printf("Hello world\n");
    return 0;
}
```

## 八、图片
- 使用图床保存图片并实现插入
  [路过图床]: https://imgse.com/
- 使用markdown语法插入
[![pFZHwAe.jpg](https://s11.ax1x.com/2024/01/23/pFZHwAe.jpg)](https://imgse.com/i/pFZHwAe)
