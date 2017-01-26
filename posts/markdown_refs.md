# 标题:
一级标题到六级标题：

    # this is an h1 tag
    ## this is an h2 tag
    ### this is an h3 tag
    #### this is an h4 tag
    ##### this is an h5 tag
    ###### this is an h6 tag


# 加粗、斜体
    *This text will be italic.* _This will also be italic._
    
    **This text will be bold.** __This will also be bold__
    
    _You **can** combine them_

*This text will be italic.* _This will also be italic._

**This text will be bold.** __This will also be bold__

_You **can** combine them_


# 列表
## 无序列表
    * item1
    * item2
    - item3
      - item3_a
      - item3_b
    - item4
* item1
* item2
- item3
  - item3_a
  - item3_b
- item4


## 有序列表
    1. Item 1
    2. Item 2
      1. item2a
      2. item2b
    3. Item 3
      * Item 3a
      * Item 3b
1. Item 1
2. Item 2
  1. item2a
  2. item2b
3. Item 3
  * Item 3a
  * Item 3b

# 图片
`![Default github avatar](https://avatars3.githubusercontent.com/u/13692447?v=3&s=460)`

![Default github avatar](https://avatars3.githubusercontent.com/u/13692447?v=3&s=460)

# 链接
可以是相对url或绝对url

    http://github.com - automatic!
    
    [GitHub](http://github.com)

http://github.com - automatic!

[GitHub](http://github.com)

# 引用
    As Kanye West said:
    > We're living the future so
    > the present is our past.
As Kanye West said:
> We're living the future so
> the present is our past.

# 段落和换行
在文本后面输入空行即可开始新的段落

# 字条转义
使用\转义markdown标识字符


# github支持的语法格式
## 代码段,支持语法高亮
    ```javascript
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    ```
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

    ```python
    def foo():
        if not bar:
            return True
    ```
```python
def foo():
    if not bar:
        return True
```

## 任务列表
在一个issue的首个comment中包含task list，就会在issue列表中显示该issue进度
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item


## 表格
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

## SHA引用
所有SHA-1的引用都会自动成为一个链接，指向该commit

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

## @mention
@username将会通知某个用户查看该comment, @teamename会通知某个组。

## 自动链接
所有的url会自动成为一个链接

## 删除线
`this is ~~strikethrough~~`
this is ~~strikethrough~~

## Emoji
输入:EMOJICODE:即可输入emoji表情

`@octocat :+1: This PR looks great - it's ready to merge! :shipit:`

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

更多表情可查看[emoji cheat-sheet](http://www.webpagefx.com/tools/emoji-cheat-sheet/)
