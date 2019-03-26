1. CSS使用方式
- 内联式
`<p style="color:red;">hello world</p>`
- 嵌入式
```
<head>
  <style>
    p{
      color:red;
      font-size:20px;
    }
  </style>
</head>
```
- 外部式 
`<link href="a.css" rel="stylesheet" type="text/css" />`
> 三种写法优先级：内联>嵌入>外部