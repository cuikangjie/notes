# ie8下Array Length 问题

![Length](../study/img/ie8Length.png)

> 在IE8下length值为21，实际数据长度为20，原因是IE8遵循ECMAScript3的规则，
当对象最后一个逗号后面没有内容时，也将最后一个空对象算在长度内，ECMAScript5
则会忽略此对象。
