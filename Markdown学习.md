目录：

[TOC]
#Header1
test
#Header2：代码块
```language
friend.post('/friend/addFollowing/:following_id', function (req, res) {
    if (chkLogin(req)) {
        var current_id = req.session.user.id;
        var following_id = req.params.following_id;
    }
});
```
显示代码块。
###Header3：区域块（用来添加引用）
>这
>是
>区域块
>```language
>friend.post('/friend/addFollowing/:following_id', function (req, res) {
    if (chkLogin(req)) {
        var current_id = req.session.user.id;
        var following_id = req.params.following_id;
    }
});
```
>可以和代码块结合使用

###列表
####无序列表
*	无序列表1
1.有序列表
2.在输入有序列表前的1.2.这些数字时，如果不跟空格，则是以上级为父级元素；
3.若输入空格，再输入，则是跟上级无序列表同级元素。
*	无序列表2
1. 这时输入了空格。
2. 看看效果。
		friend.post('/friend/addFollowing/:following_id',
    		function (req, res) {
    		if (chkLogin(req)) {
        	var current_id = req.session.user.id;
        	var following_id = req.params.following_id;
    	}
		});

直接输入4个空格或1个制表符，即可以更方便地插入代码块。

####分割线：

- - -


-----

------------

* * *


*****

####特殊字符：
&copy;
&gt;
&lt;
&amp;

####链接：
This is [WeParty](128.199.197.74:3000 "WeParty");
参考式链接：
This is [Baidu] [test];
[test]:http;//www.baidu.com "百度"
后面的双引号为Title说明；

自动链接：
<http://www.baidu.com>
邮箱地址：
<address@example.com>

####其他写法：
小段代码说明：`console.log("Test!")`测试。
== 高亮测试` console.log("Hightlight！")` ==

特殊字形：
* ** 加粗**
* *斜体*
* ~~划去效果~~
* ^这是上标效果^
* ~这是下标效果~

Todo List：
- [ ]这是1
- [ ] 这是2
- [x] 这是默认勾选中

| 表头1 | 表头2 | 表头3 |
|--------|--------|
|第一行|内容1|内容2|
|第二行|内容3|内容4|

####图片
![image alt text](image src)
参考式写法：
![image alt text][id]
[id]: src "optional title attribute"
