## 记录一下.md文档语法
## 1.标题
```
在文字前写#,注意文字与#之间有一个空格
大标题（一级标题）：在文本下面加等于号，那么上方的文字就变成了大标题，等于号的个数无限制，但一定要大于0
中标题（二级标题）：在文本下面加下划线，那么上方的文本就变成了中标题，下划线个数无限制，中标题比大标题低一级
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
* 列表一  星号后面要有一个空格，否则为普通星号
* 列表二
* 列表三
二级圆点、三级圆点：多加一个Tab，即第二行一个Tab，第三行两个Tab
  * 列表一
    * 列表二
      * 列表三
>缩进一
>>缩进二
>>>缩进三
>>>>缩进四
>>>>>缩进五

```
以此类推 
或者用连续的减号或等号写在文字之下：

```
---  分界横杠
-    无序列表
```

## 2.粗体斜体
```
**这个是粗体**
*这个是斜体*
***这个是粗体加斜体***
```
## 3.代码块
```
键盘Exc下面的按钮```,要实现语法高亮那么只要在 ``` 之后加上你的编程语言即可（忽略大小写）
```

## 4.表
```
|列名1|列名2|列名3|列名4|
|:---|:---|:---|:---|
|列1的内容1|列2的内容1|列3的内容1|列4的内容1|
|列1的内容2|列2的内容2|列3的内容2|列4的内容2|
```
## 效果如下
|列名1|列名2|列名3|列名4|
|:---|:---|:---|:---|
|列1的内容1|列2的内容1|列3的内容1|列4的内容1|
|列1的内容2|列2的内容2|列3的内容2|列4的内容2|


以此类推 
## 5. 链接
```
[会显示出来的描述](跳转网址)
[点击前往谷歌搜索](https://www.baidu.com/)
```
这里直接给个例子吧：
[点击前往百度搜索](https://www.baidu.com/)

## 6. 图片
建议的做法是现将readme.md里面要展示的图片放到仓库里面，再调用图片链接，当然直接调用网络上已经有的图片地址是面有问题的。显示图片的写法：

```
![这个括号里写的在图片加载失败时显示](图片网址)
URL写法：http://github.com/自己的用户名/项目名/raw/分支名/存放图片的文件夹/文件夹里的图片名字
在github网页打开图片，浏览器显示的网址就是图片的地址了。 
```
举例：

![头像](https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg) 
```
大得屏幕都显示不完了，下面举例怎么控制图片尺寸。
<img src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg" width="150" height="150" alt="图片加载失败时，显示这段字"/>
```
<img src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg" width="150" height="150" alt="图片加载失败时，显示这段字"/>

```
接着如果又想让图片居中：
<div align=center><img width="150" height="150" src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>
```
<div align=center><img width="150" height="150" src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>

该文档格式参考：[Github Markdown格式](https://guides.github.com/features/mastering-markdown/),
[Github Markdown格式](https://github.com/DavidAnson/markdownlint/blob/v0.11.0/doc/Rules.md#md022)
