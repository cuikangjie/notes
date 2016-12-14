# JsonExportExcel


#### 使用方法

1.引入js

```html
<script src="js/xlsx.full.min.js"></script>
<script type="text/javascript" src="js/jsonToExcel.min.js"></script>
```

2.js代码

```javascript  
var option={};   

option.data=[{a:1,b:2},{a:2,b:3}];   

var toExcel=new EcportJsonExcel(option);   

toExcel.saveExcel();
```

option
* data 数据源    
```javascrip
<!--两种形式-->
<!--第一种 object-->
[{one:11,two:12},{one:21,two:22}]
<!--第二种 arrary-->
[[11,12],[21,22]];
```
效果

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/4048654-730785e45a006b55.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


* filter 列过滤(只有在data为object下起作用)
```javascript
option.filter=['two','one'];
```
效果：


![Paste_Image.png](http://upload-images.jianshu.io/upload_images/4048654-52091d93d42591eb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


* fileName 下载文件名(默认：download)
