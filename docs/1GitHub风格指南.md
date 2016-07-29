# Github风格指南

## 语法高亮

推荐使用如下形式实现语法高亮（3个反引号）：

```markdown
'''javascript
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
'''
```

也可使用4个空格缩进。

## 任务列表

```markdown
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

## 表格

表格头部与内容间使用`-`隔开，列间使用`|`隔开：

```markdown
| Header One     | Header Two     |
| :------------- | :------------- |
| Item One       | Item Two       |
```

## SHA references

所有commit[SHA-1 hash](http://en.wikipedia.org/wiki/SHA-1)都会自动转换为指向对应GitHub地址的链接：

```markdown
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```

## 项目中的Issue references

指向Issue或Pull Request的数字自动转换为对应链接：

```markdown
#1
mojombo#1
mojombo/github-flavored-markdown#1
```

## 提醒

在用户或团队名前添加`@`提醒对应用户或团队：

```markdown
@github/support 此次提交如何？
```

呈现为： [github/support](??)此次提交如何？

## 自动链接

所有链接（如`http://www.github.com/`）都会自动转换为可点击形式。

## 中划线

在`~~`之间的内容会被加上中中划线。

## Emoji

在`:`间添加对应Emoji代码可呈现对应表情符。比如`:+1:`表示会被:+1:代替。

可在<http://emoji-cheat-sheet.com/>查看所有表情符和对应代码。
