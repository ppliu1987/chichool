复习
互动
幽默
总结
成果

第一课：
	1.欢迎  相互认识，自我介绍
	2.为什么学编程
		未来，黑客及互联网前进
		未来是人工智能的时代，代码是一项基本技能
		老师期望的目标是通过学习编程，将编程的思想和方法应用的实际的学习和生活中
	3.课程介绍
		课程规划
		课程顺序
			页面
			后端-Java or  Python
			算法&网络
		为什么先从页面开始学
			先易后难，容易入门
			所见即所得，提前兴趣
	4.课程目标
		清华 北大首页
		学校主页，家庭照片墙  动态页面
	5.介绍浏览器，浏览器在互联网中的作用
	6.网页的构成
		文字 图片（动态图片）  视频  音频   按钮
	7.网页的三大组成元素
		HTML(hyperText markup language)  CSS(cascading style sheet)  JavaScript(js)
	8.网页三大组件的作用及演示（首课演示文档firstclass_show.html）
		html + css  可以做出你看到的任何静态网页
	9.什么是静态网页?什么是动态网页?
		没有javascript参与的网页就是静态网页
		通过dynamic_show.html
	课后总结
	课堂成果
第二课：
	课前预习：
	1.文件
	2.文件扩展名
		文件的组成=文件名（给人看的）+扩展名(也叫后缀)（给电脑看的）
		.后缀是不影响文件的,只影响电脑去读这个文件
		.pptx .xlsx .docx .txt  .jpg .mp3 .mp4  .html  .jsp  自定义扩展名 .aaa .bbb
	3.编辑器
	4.标签
	5.标签分类
	6.具体标签学习
		<!DOCTYPE html>
		<html>--跟标签 只能有一个  所有的只能写它里面
		<head>--头标签 只能有一个  他里面的内容是展示给电脑看的
		<body>--体标签 只能有一个  他里面的内容是展示给人看的
		<meta>  不写meta展示乱码
		<title>--只显示第一个
		<!-- -->
		<br/> blank row
		<hr/>horizontal rule
		<h1>--<h6>独占一行,字体加粗,字体变大
		<p>this is a paragraph!</p>独占一行
	7.单双标签的寓意讲解
	8.ctrl+c   ctrl+s  ctrl+v   F5刷新
	课后总结：
第三课：
	课前预习：
	都是文字相关的标签处理
	
	行内元素,块内元素
	
	特殊符号
	空格,回车是英文单词分隔符  &nbsp;  &lt;  &gt;   https://www.jb51.net/onlineread/htmlchar.htm
	
	标签嵌套<em><strong>斜体加粗<strong></em>注意标签包裹方式.谁嵌套谁无所谓
	<small>	定义小号文本。
	<big>定义大号文本。
	<em>	定义强调文本。斜体
	<strong>	定义语气更为强烈的强调文本。 加粗
	<i>语义斜体
	<b>	定义粗体文本。
	<sup>	定义上标文本。&nbsp;m<sup>2</sub>
	<sub>	定义下标文本。O<sub>2</sub>
	<u>	不赞成使用。定义下划线文本。
	<center>	不赞成使用。定义居中文本。
	<del>	定义被删除文本。
	<mark>	定义有记号的文本。。
	课后总结：
第四课：
	课前预习：
	标签的name属性不能用中文
	form_show.html
	<form>	定义供用户输入的 HTML 表单。
	<input>	定义输入控件。
	<button>	定义按钮。
	<select>	定义选择列表（下拉列表）。
	<option>	定义选择列表中的选项。
	<label>	定义 input 元素的标注。
	<radio>  定义单选按钮
	课后总结：
第五课：
	课前预习：
	<table>	定义表格
	<caption>	定义表格标题。
	<th>	定义表格中的表头单元格。
	<tr>	定义表格中的行。
	<td>	定义表格中的单元。
	<div>	定义文档中的节。
	<span>	定义文档中的节。
	课后总结：
第六课：
	课前预习：
	<ul>	定义无序列表。
	<ol>	定义有序列表。
	<li>	定义列表的项目。
	<img>	定义图像。
	<audio>	定义声音内容。
	<source>	定义媒介源。
	<track>	定义用在媒体播放器中的文本轨道。
	<video>	定义视频。
	<a>	定义锚。
	引入css
	课后总结：
第七课：
	课前预习：
	css文件是以.css结尾
	css的4中引入方式
		1.内联样式,行内样式-耦合,代码冗余,不易维护
		2.内部样式,比行内样式灵活,代码与HTML文档样式耦合,只能装饰一个HTML文档
		3.链接外部样式文件link .css文件  推荐使用
		4.导入外部样式文档,<style>@import url("样式文件路径") 或者  @import "样式文件路径"</style>  会造成闪屏,不推荐使用
		权重内联>内部>import>link
	
	css选择器
		id选择器
		class选择器,class属性值可以有多个,用空格隔开
		标签选择器
		*通配符选择器
		选择器的权重原则--最小范围原则
	属性名="属性值"
	font	在一个声明中设置所有字体属性。	1
	font-family	规定文本的字体系列。	1
	font-size	规定文本的字体尺寸。	1
	font-style	规定文本的字体样式。	1
	font-weight	规定字体的粗细。
	
	color	设置文本的颜色。	1
	letter-spacing	设置字符间距。	1
	line-height	设置行高。	1
	text-align	规定文本的水平对齐方式。
	
	opacity	规定元素的不透明级别。
	background	在一个声明中设置所有的背景属性。	1
	background-color	设置元素的背景颜色。	1
	background-image	设置元素的背景图像。	1
	
	课后总结：
第八课：
	课前预习：
	行内元素  块内元素
	盒子模型  margin-border-padding
	
	width: 宽
	height:长
	
	border	在一个声明中设置所有的边框属性。	1
	border-bottom	在一个声明中设置所有的下边框属性。	1
	border-bottom-color	设置下边框的颜色。	2
	border-bottom-style	设置下边框的样式。	2
	border-bottom-width	设置下边框的宽度。	1
	border-color	设置四条边框的颜色。	1
	border-left	在一个声明中设置所有的左边框属性。	1
	border-left-color	设置左边框的颜色。	2
	border-left-style	设置左边框的样式。	2
	border-left-width	设置左边框的宽度。	1
	border-right	在一个声明中设置所有的右边框属性。	1
	border-right-color	设置右边框的颜色。	2
	border-right-style	设置右边框的样式。	2
	border-right-width	设置右边框的宽度。	1
	border-style	设置四条边框的样式。	1
	border-top	在一个声明中设置所有的上边框属性。	1
	border-top-color	设置上边框的颜色。	2
	border-top-style	设置上边框的样式。	2
	border-top-width	设置上边框的宽度。	1
	border-width	设置四条边框的宽度。	1
	outline	在一个声明中设置所有的轮廓属性。	2
	outline-color	设置轮廓的颜色。	2
	outline-style	设置轮廓的样式。	2
	outline-width	设置轮廓的宽度。	2
	border-bottom-left-radius	定义边框左下角的形状。	3
	border-bottom-right-radius	定义边框右下角的形状。	3
	border-image	简写属性，设置所有 border-image-* 属性。	3
	border-image-outset	规定边框图像区域超出边框的量。	3
	border-image-repeat	图像边框是否应平铺(repeated)、铺满(rounded)或拉伸(stretched)。	3
	border-image-slice	规定图像边框的向内偏移。	3
	border-image-source	规定用作边框的图片。	3
	border-image-width	规定图片边框的宽度。	3
	border-radius	简写属性，设置所有四个 border-*-radius 属性。	3
	border-top-left-radius	定义边框左上角的形状。	3
	border-top-right-radius	定义边框右下角的形状。	3
	box-decoration-break		3
	box-shadow	向方框添加一个或多个阴影。	3
	
	
	课后总结：
第九课：
	课前预习：
	选择器
	
	margin	在一个声明中设置所有外边距属性。	1
	margin-bottom	设置元素的下外边距。	1
	margin-left	设置元素的左外边距。	1
	margin-right	设置元素的右外边距。	1
	margin-top	设置元素的上外边距。
	
	padding	在一个声明中设置所有内边距属性。	1
	padding-bottom	设置元素的下内边距。	1
	padding-left	设置元素的左内边距。	1
	padding-right	设置元素的右内边距。	1
	padding-top	设置元素的上内边距。
	课后总结：
第十课：
	课前预习：
	position定位
	课后总结：
第十一课：
	课前预习：
	课后总结：
第十二课：
	课前预习：
	课后总结：
第十三课：
	课前预习：
	课后总结：
第十四课：
	课前预习：
	课后总结：
第十五课：
	课前预习：
	课后总结：
第十六课：
	课前预习：
	课后总结：
第十七课：
	课前预习：
	课后总结：
第十八课：
	课前预习：
	课后总结：
第十九课：
	课前预习：
	课后总结：
第二十课：
	课前预习：
	课后总结：
第二十一课：
	课前预习：
	课后总结：
第二十二课：
	课前预习：
	课后总结：
第二十三课：
	课前预习：
	课后总结：
第二十四课：
	课前预习：
	课后总结：
第二十五课：
	课前预习：
	课后总结：
第二十六课：
	课前预习：
	课后总结：
第二十七课：
	课前预习：
	课后总结：
第二十八课：
	课前预习：
	课后总结：
第二十九课：
	课前预习：
	课后总结：
第三十课：
	课前预习：
	课后总结：
	
	
	
属性,在js之前加上属性讲解