---
title: HTML入门学习笔记
date: 2021-04-03 11:23:43
---
> 对功能模块代码进行注释尤为重要

> ## 文字标签
>
> | 标签   | 语义                  | 说明 |
> | :----- | :-------------------- | :--- |
> | strong | strong（强调）        | 粗体 |
> | em     | emphasized（强调）    | 斜体 |
> | sup    | superscripted（上标） | 上标 |
> | sub    | subscripted（下标）   | 下标 |
>
> ## 自闭合标签
>
> | 标签      | 说明                             |
> | :-------- | :------------------------------- |
> | <meta />  | 定义网页的信息（供搜索引擎查看） |
> | <link />  | 引入“外部CSS文件”                |
> | <br />    | 换行标签                         |
> | <hr />    | 水平线标签                       |
> | <img />   | 图片标签                         |
> | <input /> | 表单标签                         |
>
> ## 有序列表标签
>
> ```html
> <ol type="属性值">
>     <li>列表项</li>
>     <li>列表项</li>
>     <li>列表项</li>
> </ol
> ```
>
> ## 无序列表标签
>
> ```html
> <ul>
>     <li>列表项</li>
>     <li>列表项</li>
>     <li>列表项</li>
> </ul>
> ```
>
> ## 定义列表标签
>
> ```html
> <dl>
>     <dt>HTML</dt>
>     <dd>制作网页的标准语言，控制网页的结构</dd>
>     <dt>CSS</dt>
>     <dd>层叠样式表，控制网页的样式</dd>
>     <dt>JavaScript</dt>
>     <dd>脚本语言，控制网页的行为</dd>
> </dl>
> ```
>
> ## 表格标签
>
> > 完整语义化及合并行列的用法
>
> ```html
> <!DOCTYPE html> 
> <html>
> <head>
>     <meta charset="utf-8" />
>     <title>编程题</title>
>     <style type="text/css">
>         table,tr,td{border:1px solid silver;}
>     </style>
> </head>
> <body>
> 	<table>
> 		<caption>学生成绩表</caption>
> 		<thead>
> 			<tr>
> 				<th>姓名</th>
> 				<th>性别</th>
> 				<th>成绩</th>
> 			</tr>
> 		</thead>
> 		<tbody>
> 			<tr>
> 				<td>张三</td>
> 				<td>男</td>
> 				<td>250</td>
> 			</tr>
> 			<tr>
> 				<td>李四</td>
> 				<td>男</td>
> 				<td>520</td>
> 			</tr>
> 		</tbody>
> 		<tfoot>
> 			<tr>
> 				<td>平均分</td>
> 				<td colspan="2">385</td>
> 			</tr>
> 		</tfoot>
> 	</table>
> </body>
> </html>
> ```
>
> > 效果图 
>
> ![](https://cdn.jsdelivr.net/gh/csong01/picgo@master/img/QQ%E6%88%AA%E5%9B%BE20210328152741.png)
>
> ## 图片标签
>
> ```html
> <body>
>     <img src="img/1.jpg" alt=""/><br/>
>     <img src="img/2.png" alt=""/><br/>
>     <img src="img/3.gif" alt=""/>
> </body>				
> ```
>
> ## a标签(超链接)
>
> ```html
> <body>
>     <a href="http://www.lvyestudy.com" target="_blank">绿叶学习网</a>
> </body>
> ```
>
> ## 表单
>
> 单选框，多选框的Name属性不要忘。暂时可以用该代码来调整位置。
>
> ```html
> &nbsp;
> ```
>

