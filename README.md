
# xdlines
> 一个简单的jQuery扩展，可以实现对单行、多行文本的溢出处理。    

### 使用方式  

1. 在页面引入jQuery和xdlines
```html
  <script src="https://cdn.bootcss.com/jquery/3.2.1/jquery.min.js"></script>
  <script src="实际文件路径/dlines.jquery.min.js" type="text/javascript" charset="utf-8"></script>
````

2. 选中文字所在标签，调用xdlines()并传入参数
```javascript
$('.el').xdlines({
    max:3  //设置文本的最大行数
})
```

### 例子

项目中有个demo.html文件，里面有完整的例子。

### 更新记录

> 2017.04.11
>> 解决了通过同一个类处理多个文本时，文本内容出错的问题
