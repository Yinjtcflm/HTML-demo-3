# HTML常用标签

## 一.a标签

    <a></a>

### 超链接标签，用于在效果中定义一个可以点击跳转的链接

### 属性
* href:超链接跳转的路径(必有属性)
* target:目标
* download:下载(很多浏览器都不支持)
* rel=noopner(为了防止一个bug)
### 作用
* 跳转外部页面
* 跳转到内部锚点
* 跳转到邮箱或电话等
## 1.a的href的取值
### 网址
* https://baidu.com
* http://baidu.com
* //baidu.com
### 路径
* /a/b/c以及a/b/c
* index.html以及./index.html
### 伪协议
* JavaScript:代码;
* mailto:邮箱
* tel:手机号
### id
* href=#xxx
  
### 示例
    <a href="http://www.baidu.com">百度</a>
    <a href="a/b/c.html">链接到c.html</a>
    <a href="javascript:alert(1)">JavaScript伪协议</a>  
    <a href="#xxx">查看xxx</a>跳转到指定标签
    <a href="mailto:邮箱">发邮件</a>  
    <a href="tel:电话号码">打电话</a> 

## 2.a的target的取值
### 内置名字
* _blank 在新的页面打开
* _top 在最顶层页面打开
* _parent 在当前层级的上一层打开
* _self 在当前页面打开
### 程序员命名
* Window的name
* iframe的name
## 二.img标签
### 图片标签
作用
* 发出get请求，展示一张图片
属性
* alt：图片加载失败时显示文字
* height:高度
* width:宽度（不要同时改变宽度和高度）
* src：图片地址

事件
* onload
* onerror（用于在控制台查看图片加载情况）
响应式
* max-width:100%（适应各种页面比例不失调）
  
可替换元素

图片示例
        <img src="1.jpg" alt="夏目友人帐">

## 三.table标签
### 表格标签

1.相关的标签
* table
* thead：表格头部
* tbody：表格身体
* tfoot：表格脚部
* tr：table row 里面的一行
* td: table data 里面的数据
* th: table head 表头
  
2.相关的样式
* table-layout
* border-collapse
* border-spacing
  
示例

        <table>
        <thead>
            <tr>
                <th>英语</th>
                <th>翻译</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>hyper</th>
                <th>超级</th>
            </tr>
            <tr>
                <th>target</th>
                <th>目标</th>
            </tr>
            <tr>
                <th>error</th>
                <th>错误</th>
            </tr>
           
        </tbody>
        <tfoot>
            <tr>
                <td>空</td>
                <td>空</td>

            </tr>
        </tfoot>
    </table>

## 我的感想
   上课看方方老师在视频里教的感觉很简单，自己实际操作下来才发现很容易出错，第三次的博客自此完成啦。

    
 