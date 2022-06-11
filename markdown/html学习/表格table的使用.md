# 创建表格的基本语法
```html
<!-- 创建表格的基本语法 -->
<table>
    <tr>
        <td>单元格内的文字</td>
         <td>单元格内的文字</td>
          <td>单元格内的文字</td>
    </tr>
</table>
```
> - `table`用于定义一个表格标签
> - `tr`用于定义表格中的行
> - `td`用于定义表格中的单元格，必须嵌套在`<tr></tr>`标签中
> - 字母`td`指表格数据(table data)，即数据单元格的内容，现在我们明白，表格最合适的地方就是用来存储数据的
> - `th` 表头单元格
> - `caption` 表格标题

# 实操
```html

    <table border="1" width="500px" height="200px" align="center" cellspacing="5px"> 
        <caption>信息收集表</caption>
        <tr>
            <th>姓名</th>
            <th>年龄</th>
            <th>性别</th>
        </tr>
        <tr>
            <td>李明</td>
            <td>18</td>
            <td>男</td>
        </tr>
        <tr>
            <td>小红</td>
            <td>18</td>
            <td>女</td>
        </tr>
    </table>


    <hr>
    <table align="center" cellpadding="22px" width="600px" height="300px" border="1px" cellspacing="0px">
<caption>小说排行榜</caption>
<tr>
    <th>排名</th>
    <th>关键词</th>
    <th>趋势</th>
    <th>今日搜索</th>
    <th>最近七日</th>
    <th>相关链接</th>
</tr>
<tr>
    <td>1</td>
    <td>鬼吹灯</td>
    <td>↓</td>
    <td>345</td>
    <td>123</td>
    <td><a href="#">贴吧</a></td>
</tr>
<tr>
    <td>2</td>
    <td>盗墓笔记</td>
    <td>↑</td>
    <td>3000</td>
    <td>23123</td>
    <td><a href="#">贴吧</a></td>
</tr>
<tr>
    <td>3</td>
    <td>西游记</td>
    <td>↑</td>
    <td>3424</td>
    <td>234234</td>
    <td><a href="#">贴吧</a></td>
</tr>
    </table>
```
**效果**
![halo/20220611095220_4a7cee67e888e43fc263e3b3a2d255aa.png](https://halo-1257218791.cos.ap-beijing.myqcloud.com/halo/20220611095220_4a7cee67e888e43fc263e3b3a2d255aa.png)
# 表格标签属性
> **表格属性写在`<table>`标签内**

## 表格属性
| 属性名          |                   含义                   | 常用属性值                |
| --------------- | :--------------------------------------: | ------------------------- |
| **border**      |  设置表格的边框，默认border="0"，无边框  | **像素值**                |
| **cellspacing** |   设置单元格与单元格边框之间的空白间距   | **像素值（默认为2像素）** |
| **cellpadding** | 设置单元格内容与单元格边框之间的空白间距 | **像素值(默认为1像素)**   |
| **width**       |               设置表格宽度               | **像素值**                |
| **height**      |               设置表格高度               | **像素值**                |
| **align**       |      设置表格再网页中的水平对齐方式      | **left,center,right**     |

## 表格属性说明
![halo/20220611092945_50aab1879aa2614b4e52fc1b7ddfa7d4.png](https://halo-1257218791.cos.ap-beijing.myqcloud.com/halo/20220611092945_50aab1879aa2614b4e52fc1b7ddfa7d4.png)

# 合并单元格
