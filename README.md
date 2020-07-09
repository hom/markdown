# Markdown
Awesome markdown usage:heartbeat:

## 目录

- [标题](#标题)
- [文本](#文本)
- [列表](#列表)
- [块引用](#块引用)
- [代码块](#代码块)
- [表格](#表格)
- [链接](#链接)
- [图片](#图片)
- [GitHub](#GitHub)

## 标题

```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

效果

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

## 文本

### 普通文本

这是一行普通文本

### 单行文本

    开头添加一个Tab或者4个空格

### 文本块

#### 语法

- 在连续的几行开头添加一个Tab或者4个空格
- 或者使用三个反引号包括  

```text
第一行文本
第二行文本
第三行文本
```

### 文字高亮

使用一对反引号``(`)``包括起来

```markdown
`linux`
```

效果

`linux`

### 换行

行尾添加两个空格或者两行之间空一行

### 显示横线效果  

```markdown
---
***
___
```

效果

---
***
___

### 斜体、粗体、删除线

   汉字   |  效果
---------|---------
`*斜体*`或者`_斜体_`  | *斜体*
`**粗体**`或者`__粗体__`| **粗体**
`~~删除线~~`|~~删除线~~
`***斜粗体***`或者`___斜粗体___`|***斜粗体***
`*~~斜体删除线~~*`或者`_~~斜体删除线~~_`|*~~斜体删除线~~*
`**~~粗体删除线~~**`或者`__~~粗体删除线~~__`|**~~粗体删除线~~**

## 列表

### 无序列表

```markdown
-
+
*
```

效果

- 无序列表
- 无序列表
- 无序列表

#### 多级无序列表

```markdown
- 一级列表
  - 二级列表
    - 三级列表
```

效果

- 一级无序列表
  - 二级无序列表
    - 三级无序列表

### 有序列表

```markdown
1.
2.
3.
```

效果

1. 有序列表
2. 有序列表
3. 有序列表

#### 多级有机列表

```markdown
1. 一级有序列表
    1. 二级有序列表
        1. 三级有序列表
2. 一级有序列表
    1. 二级有序列表
        1. 三级有序列表
3. 一级有序列表
    1. 二级有序列表
        1. 三级有序列表
```

效果

1. 一级有序列表
    1. 二级有序列表
        1. 三级有序列表
2. 一级有序列表
    1. 二级有序列表
        1. 三级有序列表
3. 一级有序列表
    1. 二级有序列表
        1. 三级有序列表

### 复选框列表

> Tip
> > 在GitHub的issue中使用该语法是可以实时点击复选框来勾选或解除勾选的，而无需修改issue原文

```markdown
- [x] 需求分析
- [x] 系统设计
- [x] 详细设计
- [ ] 编码
- [ ] 测试
- [ ] 交付
```

#### 效果

- [x] 需求分析
- [x] 系统设计
- [x] 详细设计
- [ ] 编码
- [ ] 测试
- [ ] 交付

## 块引用

### 引用文本

```markdown
> 引用文本内容
```

效果

> 引用文本内容

### 块引用多级结构

```markdown
> 数据结构
>> 树
>>> 二叉树
>>>> 平衡二叉树
>>>>> 满二叉树
```

效果

> 数据结构
>> 树
>>> 二叉树
>>>> 平衡二叉树
>>>>> 满二叉树

## 代码块

```markdown
```[编程语言]
code
```结束
```

效果

```js
function consoleIt(param) {
  console.log(param);
}
```

## 表格

### 简单表格

```markdown
表头 | 表头 | 表头
----|------|----
内容 | 内容 | 内容
内容 | 内容 | 内容
内容 | 内容 | 内容
```

或者美观一些

```markdown
| 表头 | 表头 | 表头 |
|-----|------|-----|
| 内容 | 内容 | 内容 |
| 内容 | 内容 | 内容 |
| 内容 | 内容 | 内容 |
```

效果

表头 | 表头 | 表头
----|------|----
内容 | 内容 | 内容
内容 | 内容 | 内容
内容 | 内容 | 内容

### 对齐文本

```markdown
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
```

效果

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

## 链接

### 简单链接

```markdown
<URL>或者<Email>
```

效果

<https:///www.baidu.com>  
<1234567890@qq.com>

### 一般链接

> `[name](URL title)`

- `name`显示的链接文字
- `title`鼠标悬浮显示的文字

```markdown
[百度一下，你就知道](https://www.baidu.com "百度一下，你就知道")
```

效果

[百度一下，你就知道](https://www.baidu.com "百度一下，你就知道")

### 图片链接

```markdown
[![百度一下，你就知道](https://www.baidu.com/img/bd_logo1.png "百度一下，你就知道")](https://www.baidu.com)
```

效果

[![百度一下，你就知道](https://www.baidu.com/img/bd_logo1.png "百度一下，你就知道")](https://www.baidu.com)

### 锚点

- 每一个标题都是一个锚点
- 标题中的英文字母都被转化为小写字母
- 可以链接中文锚点

```markdown
[回到顶部](#readme)
```

效果  

[回到顶部](#readme)

## 图片

### 基本格式

> `![alt](URL title)`

- `alt`表示图片显示失败时的替换文本
- `title`表示鼠标悬停在图片时的显示文本（注意这里要加引号）

```markdown
![百度一下，你就知道](https://www.baidu.com/img/bd_logo1.png "百度一下，你就知道")
```

效果

![百度一下，你就知道](https://www.baidu.com/img/bd_logo1.png "百度一下，你就知道")

## GitHub

### diff

```diff
+++ new commit line change
--- old line
```

## 使用`Css`样式

### 折叠
使用`details`和`summary`来实现折叠，点击[此处](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)查看具体文档
<details>
    <summary>Details</summary>
    
    ```js
    function hello() {
      console.log('this is in details block')
    }
    ```
</details>


