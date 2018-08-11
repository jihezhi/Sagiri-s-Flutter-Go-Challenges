# 教程0： 关于Markdown

这里的文档全部使用Markdown书写，然而一些新手可能不了解Markdown是什么。

请参阅这篇由GitHub官方出品的Markdown教程：https://guides.github.com/features/mastering-markdown/

简而言之，通过Markdown，你可以通过简单的输入达到漂亮的排版效果。比如说：

# 这是一级标题
## 这是二级标题
###### 这是六级标题

*这是斜体*
_这也是斜体_

**这是粗体**
__这也是粗体__
_你还可以**组合**它们_

* 这是项目1
* 这是项目2
  * 这是子项目2a
  * 这是子项目2b
  
1. 这是有序号的项目1
1. 这是有序号的项目2
   1. 这是有序号的子项目2a
   1. 这是有序号的子项目2b
  
http://github.com - automatic!
[这是一个通向GitHub的链接](http://github.com)

以及，

> 这是
> 一个
> 引用

我们还可以在行内添加`Hello World!`这样的代码

以及单独的代码：

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

任务列表：

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

表格:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

或者~~划掉~~内容

甚至颜文字:smile:！

强大不强大？

* 在使用Gitter的小伙伴们可以单击聊天输入框右下角的M↓图标或者在界面按下·Ctrl+Shift+m·来显示Markdown Help。
