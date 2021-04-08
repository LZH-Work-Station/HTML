# HTML5

```html
<!DOCTYPE html> 告诉浏览器我们用什么规范
```

### 注释

```html
<!--这中间是注释 -->
```

### 各种标签

- head: 网页头部

- title: 选项卡, 网站的标题,就是浏览器上那个最上面的选项卡, **title包含在head标签内**

- meta: 描述性标签, 描述我们网站的信息. 用来做SEO(Search Engine Optimization) 搜索引擎优化, meta 里有keywords, description, 标签内容放入一些关键信息,便于别人在浏览器中搜到, **meta 包含在head标签内**

- body: 是主体,我们的html主要文件都写在body里

#### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="keywords" content="第一个HTML">
    <meta name="descriptions"content="加油学习吧">

    <title>Hello World</title>
</head>
<body>
Hello World Li Zehan
</body>
</html>
```

- 各级标题标签：就是各种标题，例如主题目用h1, 后面的用h2什么的

- 段落标签：用p表示 可以按p+tab快捷键直接生成段落标签， 可以分段

- 换行标签：br 在要换行的位置使用 有点像/n，属于比较紧凑的换行，行间距很小

- 水平线标签：hr 有一个水平线，有点像word里的分割线

- 粗体：strong标签

- 斜体：em标签

- 特殊符号： 空格 &nbsp；大于号 &gt；小于号 &lt；（这里分号是中文的 在html中要变成英文的分号）

  