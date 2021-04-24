# Table标签

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>表格学习</title>
</head>
<body>

<!--border是边框的粗细-->
<table border="1px">
<!--独占第一行中的5个列表长度-->
  <tr>  <td colspan="5">爱情</td></tr>
  <tr>
<!--独占这个tr及之后的列表的2列-->
    <td rowspan="2">新人</td>
    <td>李泽汉</td>
    <td>李泽汉</td>
    <td>李泽汉</td>
    <td>李泽汉</td>
  </tr>

  <tr>
    <td>贾旖萌</td>
    <td>贾旖萌</td>
    <td>贾旖萌</td>
    <td>贾旖萌</td>
  </tr>
</table>

</body>
</html>
```

- tr: 代表一行
- td：代表这一行中的列
- border：边框粗细
- colspan：独占一行，长度为5列
- rowspan：独占一列，长度为2行