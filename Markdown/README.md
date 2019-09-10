#### 1. 基本的带快捷键的 Markdown 书写演示

`Ctrl 0`到`Ctrl 4`：普通文本、一级到四级标题；

`Ctrl B`：加粗， **这里加粗了**；

`Ctrl I`：斜体，*我斜了*；

`Ctrl U`：下划线，<u>下划线</u>；

`Shift Alt 5`：删除线，~~删除线~~；

`Shift Ctrl Tab键上面那个键`：行内代码块，`我是代码块`；

`Ctrl k`：超链接，[Markdown中文文档](https://markdown-zh.readthedocs.io/en/latest/) ， [文件夹内链接](./Untitled.md)  ， 还支持文章内锚点，请`Ctrl`点击此处 :arrow_right:[第二节](#2. 基本的不带快捷键的 Markdown 书写演示)；

​				&hearts;  [特殊字符](https://blog.csdn.net/vola9527/article/details/69948411)

`Ctrl T`：表格，支持拖拽移动、网页端表格复制转换；

| 靠左 | 居中 | 靠右 |
| ---- | :--: | ---: |
| 111  | 222  |  333 |

`Ctrl Shift Q`：引用：

> 这里是引用
>
> > 引用中还可以继续引用
> >
> > 双击`回车`可以退出引用

`Shift Ctrl I`：图片；

![img](C:\Users\Administrator\Downloads\backgroud.jpg)



#### 2. 基本的不带快捷键的 Markdown 书写演示

*部分功能需要先在配置文件中开启才能使用*

`代码块`：

```javascript
import React from 'react';
import ReactDOM from 'react-dom';
import App from './App';
import * as serviceWorker from './serviceWorker';
// import 'antd/dist/antd.css';
ReactDOM.render(<App />, document.getElementById('root')); 
serviceWorker.unregister();
```

无序列表、有序、任务列表：

+ `+` 实心圆
  - `-` 空心圆
    * `*` 小方块

1. 有序1
2. 有序2
3. 有序3

任务列表：` - [ ] XX`

- [x] 已选中

- [ ] 苹果

#### 3. 一些扩展功能

参考链接：

`[^1]` ：扒拉扒拉扒拉[^1]；

[^1]: 来自于什么什么；

上下标：

`^2^` ：上标，X^2^ ；

`~2~`：下标，H~2~O ；

`==重点==`：高亮，这句话是==重点==；

`<!--导出不显示-->`：注释，<!--这里是注释-->；

`$e^2$`：内联公式，$e^2$；

`---`：分割线，如下

---

`:up`：enjoy图标，:arrow_double_up:，:top:，:smile:

目录生成：

`[toc]`：目录的生成完全动态；

[TOC]





