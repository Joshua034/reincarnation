### Typora的markdown语法

[toc]

#### 1、标题
ctrl+数字键

#### 2、下划线

<u>Ctrl+u</u>

#### 3、删除线
~~删除线~~

#### 4、字体加粗倾斜

**粗体 Ctrl+b**

*倾斜 Ctrl+i*

#### 5、字体类型

<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>

    代码：
    <font face="黑体">我是黑体字</font>

<font color=#009999 size=7 face="宋体">color=#009999 宋体</font>

    代码：
    <font color=#00ffff size=7 face="宋体/黑体">color=#00ffff 宋体</font>

#### 6、无序列表

- 减号+Space+空格

#### 7、有序列表

1. 1和。和空格

#### 8、引用

> 引用

#### 9、加链接

[链接地址](https://www.bilibili.com/video/av32901294?p=2)

#### 10、**加图片**

1. 拖拉进来
   ![1](D:\1.png)
   
		但是图片必须放在这个绝对路径或者相对路径下，否则打不开
	
2. `![something](路径)`    路径可以本地路径或者网络地址

   ![随便一些东西](https://octodex.github.com/images/yaktocat.png)

3.  图传神器

   `先有一个放图片的服务器，然后从服务器中获取图片`

   <img src="https://i.loli.net/2020/02/01/AU2MvELXxJhSDPl.jpg" alt="th.jpg" style="zoom:200%;" />
   
   


#### 11、代码块
```java
public static void main(String[] args) {
    System.out.println("代码块示例");
}
```

#### 12、选中英文或中文

	Ctrl+d	选择单词或句子
	Ctrl+l	选择行
#### 13、搜索 替换

	Ctrl+f   Ctrl+h

#### 14、生成表格

	Ctrl+t

| 物品 |  类别  |
| :--: | :----: |
| 苹果 |  水果  |
|  鱼  | 水产品 |
| 鲸鱼 |  动物  |

#### 15、目录生成

	[toc] 加 enter

#### 16、着重关键字

`Ctrl+Shift+反引号（Tab键上面那个)`

#### 17、表情符号

`英文下的冒号加字母`

:grapes:

`在中文状态下Ctrl+Shift+b(使用微软自带的)`

😂

#### 18、页面查看

	跳转到页面最前面或最后面
	Ctrl+home
	Ctrl+Fn+home（在笔记本上） Ctrl+Fn+End

#### 19、分割线

---

`三个减号加enter`

#### 20、脚注

	文字 + [^数字]

加脚注[^9]

[^9]: great

#### 21、主题

```
https://theme.typora.io/下载主题，
拷贝.css文件到 文件->偏好设置->外观->打开主题文件夹
```

#### 22、背景色的设置
<table><tr><td bgcolor=#00ffff>背景色：</td></tr></table>
```javascript
代码：
<table><tr><td bgcolor=#00ffff>背景色：</td></tr></table>
```

