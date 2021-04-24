# href 标签

## a 标签

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>链接标签学习</title>
</head>
<body>

<a href="我的第一个html网页.html" target="_blank">点击我跳转到第一个html</a>
<br>
<a href="我的第一个html网页.html">
    <img src="../Resources/Image/JYM.jpg" alt="老婆婆头像不在了" 		title="老婆婆头像" width="300" height="400"></a>

</body>
</html>
```

- a href 标签<a>之间是显示的东西，这个例子中 第一个是一段文字，第二个是一个图片
- target：target可以是_blank 代表点击这个href会创建一个新的标签页， _self是默认的，在本标签页跳转



## 锚链接

- 直接回到顶部

```html
<!--先定义一个叫top的锚-->
<a name="top">顶部</a>

<!--跳转到刚刚定义的top锚-->
<a href='#top'>回到顶部</a>
```

- 跨网页的锚链接应用

```html
<!--例如在一个叫锚链接.html的网页里先定义一个叫top的锚-->
<a name="top">顶部</a>

<!--跳转到锚链接.html的top锚-->
<a href='锚链接.html#top'>回到顶部</a>
```

## 功能性链接

```html
<!--邮件链接-->
<a href="mailto:lzh1532805942@163.com">点击发邮件给我</a>

<!--QQ推广 好像不太行,没图片啊--> 
<a target="_blank" 	  	      href="http://wpa.qq.com/msgrdv=3&uin=&site=qq&menu=yes">
    <img border="0" src="http://wpa.qq.com/pa?p=2::52" alt="点击这里给我发消息" title="点击这里给我发消息"/></a>
```

- 第一个是邮件链接 mailto
- 第二个是QQ的一个推广链接, 有一个qq的且头像,然后可以直接进行加好友联系 

