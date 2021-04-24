# Form 标签

表单标签 是为了获取用户的input然后提交表单到后台用javascript处理

## 1. 各种input的方式

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>表单登陆注册</title>
</head>
<body>

<form action="https://www.baidu.com" method="get" name="login">
    <p>名字: <input type="text" name="username" maxlength="8" placehold="请输入用户名"></p>
    <p>密码: <input type="password" name="psd" required></p>

    <!--单选里面name相同保证两个radio是同一个组即两个radio只能选中一个-->
    <p>
        <input type="radio" value="boy" name="sex">男
        <input type="radio" value="girl" name="sex">女
    </p>
    <!--多选框 checkbox-->
    <p>
        <input type="checkbox" value="eat" name="hobby">吃
        <input type="checkbox" value="drink" name="hobby">喝
    </p>

    <!--上传文件-->
    <p>
        <input type="file" name="upload_file">
    </p>

    <!--系统自带按钮-->
    <p>
        <input type="submit">
        <input type="reset">
    </p>

    <!--自定义按钮-->
    <p>按钮
        <input type="button" value="点我一下" name="button1">
        <input type="image" src="../Resources/Image/JYM.jpg" height="90" width="60" name="button2">
    </p>
    
    <!--邮箱-->
    <p>
        <input type="email" name="email">
    </p>

    <!--URL-->
    <p>
        <input type="url" name="url">
    </p>

    <!--数字-->
    <p>
        <input type="number" name="num" max="100" min="0" step="1">
    </p>

    <!--滑块-->
    <p>
        <input type="range" name="voice" min="0" max="100" step="2">
    </p>

    <!--搜索框-->
    <p>
        <input type="search" name="chercher">
    </p>
    
    
    <!--下拉列表, 在选项中选择-->
    <p>
        <select name="Country">
            <option value="china">中国</option>
            <option value="US">美国</option>
            <option value="RUISHI" selected>瑞士</option>
            <option value="INDIA">印度</option>
        </select>
    </p>


    <!--文本输入,例如写评论啊 反馈什么的 -->
    <p>评论
        <textarea name="textarea" cols="60" rows="10">文本内容</textarea>
    </p>
    

</form>

</body>
</html>
```

- method: 可以为GET但是请求的参数例如用户名密码会被显示在URL中，也可以为POST， 不会显示在URL中，作用相同

- action：向哪个地址提交表单

- name: 起名字为了在java中使用

- textarea: 文本输入，写评论什么的

- select: 下拉列表，selected代表为初始显示的选项

- input：

  ​	type = "text" 输入用户名什么的

  ​	type = "password" 输入的是密码类型 是黑点

  ​	type = "submit" 一个提交的按钮 会将表单里的所有勾选的和输入的信息都提交

  ​	type = "reset" 一个重置的按钮 重置表单里input里输入的内容

  ​	type = "checkbox" 多选框

  ​	type = "radio" 单选框

  ​	type = "button" 自定义按钮

  ​	type = "image" 图片按钮，会提交表单，点击效果和submit一样

  ​	type ="email" 输入邮箱

  ​	type = "url" 输入url

  ​	type = "number" 输入数字，可以用step来上下调整数字，例如淘宝里选择购买的数	量

  ​	type = "range" 滑块，用于例如调整音量大小

  ​	type = "search" 搜索框

  ​	value: 初始值

  ​	maxlength: 最大长度

## 2. 表单的权限

​	在input或者其他的form内标签的权限的改变

- readonly

- disable

- hidden

  

## 3. 鼠标增强

```html
    <!--增强鼠标可用性-->
    <label for="mouse">鼠标增强</label>
    <input type="text" id="mouse">
```

这个input的标签id为mouse，点击“鼠标增强”这个文本等同于点击text标签



## 4.对输入内容的要求

- required: 要求不能为空
- placeholder: 输入框内的提示信息
- pattern: 正则表达式 可以要求输入内容的格式 例如前面是数字后面是字母必须有大写等等



## 