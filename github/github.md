## 记录一下.md文档语法
## 1.标题
```
在文字前写#,注意文字与#之间有一个空格
# 一级标题
## 二级标题
### 三级标题
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
键盘上的esc键下的那个键:```
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
[点击前往谷歌搜索](https://www.baidu.com/)

## 6. 图片
建议的做法是现将readme.md里面要展示的图片放到仓库里面，再调用图片链接，当然直接调用网络上已经有的图片地址是面有问题的。显示图片的写法：

```
![这个括号里写的在图片加载失败时显示](图片网址)

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
效果： 
