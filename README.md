# library
一些常用的前端类库、框架，以及自己制作的less库和一些数据


此外，base64.js可以将js普通字符串转换为base64格式，因为js中的字符串默认为utf-16格式。  
这个文件里面有`utf16to8()`、`utf8to16()`、`base64encode()`、`base64decode()`四个函数，使用方法为：  
`var encodeStr = base64encode(utf16to8(str));//此为将某个字符串转换为base64代码。`  
`var decodeStr = utf8to16(base64decode(encodeStr));//将base64代码转换为字符串。`
可参考http://www.ruanyifeng.com/blog/2008/06/base64.html
