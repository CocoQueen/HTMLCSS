# [HTML基础认识](https://github.com/CocoQueen/HTMLCSS/blob/main/index.html)
```html
	<!DOCTYPE html>
	<!-- 这句声明，就是告诉浏览器，请使用HTML5的标准来解析这个网页 -->
	<html>
	<!-- 表示网页的头部，这里的信息都是对网页的整体说明 -->
		<head>
		<!-- 编码格式 -->
			<meta charset="utf-8">
			<!-- 网页标题 -->
			<title>
			</title>
		</head>
	<!-- 表示网页的主体，网页的内容都写在这里 -->
		<body>
		</body>
	</html>
```

# [001 博客](https://github.com/CocoQueen/HTMLCSS/blob/main/001%E5%8D%9A%E5%AE%A2/index.html)

```html
	<h1>1级标题</h1>
	<h2>2级标题</h2>
	<h3>3级标题</h3>
	<h4>4级标题</h4>
	<h5>5级标题</h5>
	<h6>6级标题</h6>
	&nbsp;网页上显示一个空格
	<i>斜体标签 文字会出现斜体效果 </i>
	<hr/>水平线
	<p>段落标签，文字会独占一行</p>
	<br/>换行标签
	<b>文字会出现加粗效果</b>
``` 
 
 # [002 新闻列表](https://github.com/CocoQueen/HTMLCSS/blob/main/002%E6%96%B0%E9%97%BB%E5%88%97%E8%A1%A8/index.html)
```html
<!-- <a href="http://www.baidu.com">内容内容</a> 超链接 -->
	<!-- <img src="img/icon_arrow.png" /> 图片 -->
	<!-- <ul><li>列表项目</li></ul>无序列表 -->
	<!-- <ol><li>列表项目</li></ol>有序列表 -->
	<body>
		<h1>科技&nbsp;<img src="img/icon_arrow.png"></h1>
		<hr />
		<ul>
			<li>
				<a href="http://www.baidu.com">中子星内“核面食”比钢硬100亿倍</a>
			</li>
			<li>蒂姆·库克分享新iPhone xs用户拍摄样张</li>
			<li>专家解读：中国知识付费经济向上态势明显</li>
			<li>苹果推送 macOS Mojave 正式版，你更新...</li>
		</ul>
		<ol>
			<li>
				<a href="http://www.baidu.com">中子星内“核面食”比钢硬100亿倍</a>
			</li>
			<li>蒂姆·库克分享新iPhone xs用户拍摄样张</li>
			<li>专家解读：中国知识付费经济向上态势明显</li>
			<li>苹果推送 macOS Mojave 正式版，你更新...</li>
		</ol>
	</body>
```

# [003 如何下载图片及切图](https://github.com/CocoQueen/HTMLCSS/blob/main/003%E5%9B%BE%E7%89%87%E7%9A%84%E4%BD%BF%E7%94%A8/index.html)

	下载图片 查看是否是合成图  
	如果不是就直接使用。  
	否则就用PS打卡，选择切片工具，切图完成后，ctrl+alt+shift+s保存，之后选择用户切片，得到图片后方可使用

# [004 知识点补充](https://github.com/CocoQueen/HTMLCSS/blob/main/004%E7%9F%A5%E8%AF%86%E7%82%B9%E8%A1%A5%E5%85%85/index.html)
## 关于超链接
	a标签中  
	href：链接地址  
	target：表示目标 blank表示空白（即：在空白窗口打开新的页面）
```html
<a href="http://www.baidu.com" target="_blank">点我</a>
```

## 关于无序列表
	提供了三种样式  
	1.实心圆(默认)  	disc  
	2.空心圆			circle  
	3.实心方块		square  
```html
<ul type="disc">
			<li>项目列表</li>
			<li>项目列表</li>
			<li>项目列表</li>
		</ul>
		<ul type="circle">
			<li>项目列表</li>
			<li>项目列表</li>
			<li>项目列表</li>
		</ul>
		<ul type="square">
			<li>项目列表</li>
			<li>项目列表</li>
			<li>项目列表</li>
		</ul>
```

## 关于有序列表
	提供了三种样式  
	1.数字(默认)		1  
	2.小写字母		a/A  
	3.大写罗马字母	i/I  
```html
<ol type="1">
			<li>项目列表</li>
			<li>项目列表</li>
			<li>项目列表</li>
		</ol>
		<ol type="A">
			<li>项目列表</li>
			<li>项目列表</li>
			<li>项目列表</li>
		</ol>
		<ol type="a">
			<li>项目列表</li>
			<li>项目列表</li>
			<li>项目列表</li>
		</ol>
		<ol type="i">
			<li>项目列表</li>
			<li>项目列表</li>
			<li>项目列表</li>
		</ol>
		<ol type="I">
			<li>项目列表</li>
			<li>项目列表</li>
			<li>项目列表</li>
		</ol>
```

## 关于图片
	title：鼠标滑上去时的提示  
	alt：图片加载失败后的文字
```html
<img  title="鼠标滑上去时的提示" alt="图片加载失败后的文字" src="../002新闻列表/img/icon_arrow.png" />
```

## 不常用的标签

	del 给文字添加删除线  
	sup 把文字变成上标  
	u 给文字加下划线  
	center 把文字居中
```html
		<del>哈哈哈</del>
		<sup>2</sup>
		<u>hghhahh</u>
		<center>hnfajk</center>
```

# [005 百度云盘制作](https://github.com/CocoQueen/HTMLCSS/blob/main/005%E7%99%BE%E5%BA%A6%E4%BA%91%E7%9B%98%E5%88%B6%E4%BD%9C/demo.html)
	绝对地址：在任何情况下，都可以找得到的地址  
	相对地址：必须知道当前所在，才能找到

# [006 简单表格的制作](https://github.com/CocoQueen/HTMLCSS/blob/main/006%E7%AE%80%E5%8D%95%E8%A1%A8%E6%A0%BC%E7%9A%84%E5%88%B6%E4%BD%9C/demo.html)
	table 表格标签  
	border 表格边框属性  
	cellspacing 单元格间隙  
	tr 表示行  
	td 表示单元格  
	align 排列 表示对齐方式
	col 表示一列
```html
<body>
		<h3>前端技术阶段划分标准</h3>
		<!-- table 表格标签
		border 边框
		cellspacing 单元格间隙 -->
		<table border="1px" cellspacing="0">
			<!-- align 排列 表示对齐方式 -->
			<!-- col 表示列 -->
			<col width="200px"/>
			<col width="200px"/>
			<col width="200px"/>
			<col width="200px"/>
			<col width="200px"/>
			<tr align="center">
				<td></td>
				<td>初级</td>
				<td>中级</td>
				<td>高级</td>
				<td>专家</td>
			</tr>
			<tr align="center">
				<td>标准</td>
				<td>被产品怼的说不出话</td>
				<td>跟产品互怼不相上下</td>
				<td>怼的产品没话说</td>
				<td>直接将其怼辞职</td>
			</tr>
			<tr align="center">
				<td>用户A</td>
				<td></td>
				<td></td>
				<td></td>
				<td></td>
			</tr>
			<tr align="center">
				<td>用户B</td>
				<td></td>
				<td></td>
				<td></td>
				<td></td>
			</tr>
			<tr align="center">
				<td>用户C</td>
				<td></td>
				<td></td>
				<td></td>
				<td></td>
			</tr>
		</table>
	</body>
```

# [007 个人简历的制作](https://github.com/CocoQueen/HTMLCSS/blob/main/007%E4%B8%AA%E4%BA%BA%E7%AE%80%E5%8E%86%E5%88%B6%E4%BD%9C/demo.html)
	colspan  	列合并  
	rowspan 	行合并  
```html
<tr height="40px" align="center">
				<td>姓名</td>
				<td></td>
				<td>性别</td>
				<td></td>
				<td>年龄</td>
				<td></td>
				<td rowspan="4">照片</td>
			</tr>
			<tr height="40px" align="center">
				<td>学历</td>
				<td></td>
				<td>籍贯</td>
				<td colspan="3"></td>
			</tr>
			<tr height="40px" align="center">
				<td>电话</td>
				<td></td>
				<td>政治面貌</td>
				<td colspan="3"></td>
			</tr>
```

# [008 表格知识补充](https://github.com/CocoQueen/HTMLCSS/blob/main/008%E8%A1%A8%E6%A0%BC%E7%9F%A5%E8%AF%86%E8%A1%A5%E5%85%85/demo.html)

## 关于表头 
	td 转换为th 就会出现文字加粗的效果  th=加粗并水平居中的td  
```html
<tr height="40px" align="center">
	<th colspan="7">个人简历</th>
</tr>
```

## 关于colgroup 标签
	colgroup span=6 width=100px 可以批量设置列的宽度
```html
<colgroup span="6" width="100px"></colgroup>
<colgroup span="1" width="200px"></colgroup>
```

## 关于tbody
	根据w3c的标准 一个表格应包括页眉(thead)、主体(tbody)、页脚(tfooter)三部分，其中主体部分是最重要的部分，不建议省略tbody

## 关于注释
	ctril+/

## 关于标签的嵌套
	超链接不能嵌套超链接  
	p标签不能嵌套p标签  
	标题标签(h1...h6)也不可以互相嵌套  

# [009 登录表单](https://github.com/CocoQueen/HTMLCSS/blob/main/009%E7%99%BB%E5%BD%95%E8%A1%A8%E5%8D%95/demo.html)

 ## 常见的表单控件 （input）类型(type)：
	1.text  		文字文本  
	2.password  	密码  
	3.button  		普通按钮  
	4.radio  		单选  
	5.checkbox  	复选  
	6.submit		提交按钮  
	7.reset			重置按钮  
	8.file			文件选择框  
```html
<input type="text"/>
```
	
## 表单知识点总结 
	1.form必须有action属性，表示提交地址  
	2.所有需要提交的数据，input必须有name属性  
	3.input按钮的文字，使用value属性表示  
	4.input必须放在form标签内才能提交  
	
```html
	<form action="http://www.baidu.com" method="get">
		<table width="600px" border="1px" cellspacing="0">
			<tbody>
				<tr height="40px">
					<td rowspan="4" align="center">总体信息</td>
					<td colspan="2"></td>
				</tr>
				<tr height="40px">
					<td align="right">用户名：</td>
					<td>
						<input type="text" name="loginname"/>
					</td>
				</tr>
				<tr height="40px">
					<td align="right">密码：</td>
					<td>
						<input type="password" name="pwd"/>
					</td>
				</tr>
				<tr height="40px">
					<td colspan="2" align="center">
						<input type="submit" value="提交" />
						<input type="reset" value="重置" />
					</td>
				</tr>
			</tbody>
		</table>
	</form>
```

## get请求和post请求的区别

### 从功能上划分： 提交数据(post)，获取数据(get) [form 表单method属性可以设置]
	问：既然get和post只是在传递数据的方式上不同，那是否意味着，无论获取数据还是提交数据两种方式可以混用呢？
	答：可以混用，但不建议
### 区别总结
	1.get请求通常表示获取数据
	2.post请求通常表示提交数据
	3.get请求发送的数据都写在地址栏上，用户可见
	4.post请求发送的数据用户不可见
	5.get请求不能提交大量的数据，但post可以，因此不要混用

# [010 认识CSS](https://github.com/CocoQueen/HTMLCSS/blob/main/010%E8%AE%A4%E8%AF%86CSS/demo.html)	
	1、HTML跟CSS是什么关系？
	HTML：标签和文字 组成网页
	CSS：用来修饰网页样式的语法，称为层叠样式表，cascading style sheet
	
	style:表示样式
	color:表示颜色
	...
	
# [011 容器的作用](https://github.com/CocoQueen/HTMLCSS/blob/main/011%E5%AE%B9%E5%99%A8%E7%9A%84%E4%BD%9C%E7%94%A8/demo.html)
	span:一个容器标签，不具备任何特殊功能，仅当做容器来使用，用于包裹一段文本，便于给文本增加样式。
	div:一个通用的容器标签，不具备任何特殊功能，仅当做容器来使用。可以包裹任何内容，也可以容器直接互相包裹。
```html
	<div style="color: #aa00ff;margin: auto;width: 500px;">
		<p style="text-align: center;">
			<span style="background-color: gray;color: white;font-size: 24px;">
				《生物多样性公约》缔约方大会第十五次会议开幕
			</span>
		</p>
		<p>
			<b>中国日报10月11日昆明电(记者 冯永斌 武晓慧）</b>
		
			<span style="color: aqua;">
				2021年10月11日，联合国《生物多样性公约》缔约方大会第十五次会议（COP15）第一阶段会议在云南昆明正式拉开帷幕。
			</span>
		</p>
		<p>
			本届大会主题为“生态文明：
			<b>
				共建地球生命共同体”，
			</b>
			这是联合国环境公约缔约方大会首次将“生态文明”作为大会主题。本届大会于2021年10月11日至15日和2022年上半年分两阶段在昆明召开。
		</p>
	</div>
```
	
## style样式：
	text-align:center	让内部元素水平居中
	margin:auto			让元素本身水平居中
	background-color	设定背景颜色
	font-size			设定字体大小
	color				设定文字颜色
	
# [012 布局与选择器](https://github.com/CocoQueen/HTMLCSS/blob/main/012%E5%B8%83%E5%B1%80%E4%B8%8E%E9%80%89%E6%8B%A9%E5%99%A8/demo.html)

## div容器的特点：
	一个空div，默认宽度100%，高度为0.

## 行高：
	行高默认为21px 字体大小默认为16px
	
## 内部样式表：

	写在标签内部的叫行内样式，写在style标签块中的称为内部样式，内部样式的出现，会大大简化CSS样式的编写工作
	行内样式优先级>内部样式
	
注：在实际网页开发中，作用于同一个元素上的多个样式产生冲突的情况不可避免的经常发生，当多个样式发生重叠时，优先级别高的样式会生效。
因此得名：层叠样式表，简称CSS[(013 样式表的层叠)](https://github.com/CocoQueen/HTMLCSS/blob/main/013%E6%A0%B7%E5%BC%8F%E8%A1%A8%E7%9A%84%E5%B1%82%E5%8F%A0/demo.html)
	
	
	
## CSS选择器：
	(#banner)ID选择器：id表示身份，在页面中元素的id不允许重复，因此id选择器只能选择单个元素；
	(img)标签选择器：根据标签名称选择对应的所有标签；
	(.nav)类(别)选择器：选择拥有该类别的多个元素；
	(*)通用选择器：针对页面上所有的标签都生效。
	



 