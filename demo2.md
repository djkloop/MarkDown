# Demo2

## Link

### 内嵌链接

- 外部链接: [自己的测试服务器](http://47.93.249.220/) 
- 内部链接1,链接仓库的其他文件: [demo1](demo1.md)
- 内部链接2,链接当前文档其他部分: [Code](demo2.md#Code)

### 引用式链接

- 外部链接: [自己的测试服务器]
- 外部链接: [自己的测试服务器][test]
- 内部链接1,链接仓库的其他文件: [demo1]
- 内部链接2,链接当前文档其他部分: [Code]

## Photo

- 图片markdown语法  
![alt](url text)
- 外部链接  
![baidu][baidu_logo]
- 本地文件  
![undersource][undersource_logo]

## Quote

> 这是一个引文。 --出自《xxx》
>> 二次引用

## Code

- 行内代码

这个代码是用来申明变量的 `var a = 10` ;打印内容是 `console.log(a)`.

- 块式代码

```javascript
var a = 10;
console.log(a + 'you can you up! ???!');
```



<!-- 下面是本文档种用到的链接 -->

[自己的测试服务器]: http://47.93.249.220/
[test]: http://47.93.249.220/
[demo1]: demo1.md
[Code]: demo2.md#Code
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png "百度图片6666"
[undersource_logo]: ./images/underscore.png "undersource.png"