# 作业
## 《HTML常用标签》

### 内容为：
*****
1. a标签的用法
* 属性：
   * href
   * target
   * download
   * rel=noopener
  *****
* 作用：
   * 跳转外部页面
   * 跳转内部锚点
   * 跳转到邮箱或电话等
   * 写一个网址
*****
* a的href的取值
   * 网址
   * http://google.com
   * htttps://google.com
   * //google.com
*****
* 路径
   * /a/b/c 以及a/b/c
   * index.html以及./index.html
*****
* 伪协议
   * javascript:代码
   * mailto:邮箱
   * tel:手机号
* id
   * href=#xxx     
******
* a的target取值
   * 内置名字：
      * _blank
      * _top
      * _parent
      * _self
* 程序员命名
   * window的name
   * iframe的name 
******
* a的download
   * 作用：
      * 不是打开页面，而是下载页面
   * 问题：
      * 不是所有浏览器都支持，尤其是手机浏览器可能不支持
******

2. img标签的用法
* 作用
   * 发出get请求，展示一张图片
 * 属性
    * alt/height/width/src
 * 事件
    * onload/onerror
 * 响应式
    * max-width:100%         
******

3.  table标签的用法
* 相关的标签
   * table
   * thead
   * tbody
   * tfoot
   * tr
   * td
   * th
* 相关的样式
   * table-layout
   * border-collapse
   * border-spacing   
******
4. 其他感想
* http-server -c-1可以缩写成hs -c-1
* parcel a-href.html
* /a/b/c代表根目录
* 用/开头就是绝对路径
* 不用/开头就是相对路径
* a/b/c相对于a下面的b,相对于b下面的c
* ./index.html
* index.html
* 在当前目录找index.html
* 加不加./都一样
* self是默认值，默认在当前页面打开
* _blank在空白页面打开
* _top在当前页面顶级部分，最上面的窗口打开
* _parent在当前链接所在的iframe的上一层打开
* _self默认值
* action控制请求哪个页面；method是控制用get还是post来请求
* autocomplete="on" 输入的时候给出自动的建议
* input里面不支持其他的标签，只有纯文本
* botton里面可以有任何东西，甚至可以是图片
* type里面必须有一个submit的按钮，这样表单才可以提交
* 看不见的input是自动给js填充一些id啊，字符串之类的东西
