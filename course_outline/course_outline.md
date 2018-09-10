复习
互动
幽默
典故故事
加入其它科目的知识
段子
总结
成果

成果
照片墙
学校门户
计算器
点名器
贪吃蛇
2048

第一课：
	1.欢迎  相互认识，自我介绍
	2.为什么学编程
		未来，黑客及互联网前进
		未来是人工智能的时代，代码是一项基本技能
		老师期望的目标是通过学习编程，将编程的思想和方法应用的实际的学习和生活中
	3.课程介绍
		课程顺序
			页面
			后端-Java or  Python
			算法&网络
		为什么先从页面开始学
			先易后难，容易入门
			所见即所得，培养兴趣
	4.课程目标
		清华 北大首页
		学校主页，家庭照片墙  动态页面
	5.介绍浏览器，浏览器在互联网中的作用  网页及浏览器历史（http://www.iefans.net/wangye-liulanqi-fazhan-xiangshi/）
	6.网页的构成
		文字 图片（动态图片）  视频  音频   按钮
	7.网页的三大组成元素
		HTML(hyperText markup language)标签  CSS(cascading style sheet)标签属性  JavaScript(js)改变标签属性
	8.网页三大组件的作用及演示（首课演示文档firstclass_show.html）
		html + css  可以做出你看到的任何静态网页
	9.什么是静态网页?什么是动态网页?
		没有javascript参与的网页就是静态网页
		通过dynamic_show.html
	课后总结
	课堂成果
第二课：
	前情提要：
	1.文件
	2.文件扩展名
		文件的组成=文件名（给人看的）+扩展名(也叫后缀)（给电脑看的）
		.后缀是不影响文件的,只影响电脑去读这个文件
		.pptx .xlsx .docx .txt  .jpg .mp3 .mp4  .html .htm  .jsp  自定义扩展名 .aaa .bbb
	3.编辑器
		用了查看和编辑文件的软件
		常用编辑器
			microsoft-office windows自带txt编辑器  Notepad++ UltraEdit editplus  浏览器   hbuilder dreamweaver eclipse  idea
	4.标签
	5.标签分类
	6.具体标签学习
		<!DOCTYPE html>
		<!DOCTYPE> 声明必须是 HTML 文档的第一行，位于 <html> 标签之前。
		<!DOCTYPE> 声明不是 HTML 标签；它是指示 web 浏览器关于页面使用哪个 HTML 版本进行编写的指令。
		<html>--跟标签 有且只能有一对  所有的只能写它里面
		<head>--头标签 有且只能有一对  他里面的内容是展示给电脑看的
		<body>--体标签有且 只能有一对  他里面的内容是展示给人看的
		<meta>  不写meta展示乱码
		<title>--只显示第一个
		<!-- -->注释的作用:1.添加代码说明,提高代码的易读性2.使代码无效
		<br/> blank row
		<hr/>horizontal rule
		<h1>--<h6>独占一行,字体加粗,字体变大
		<p>this is a paragraph!</p>独占一行
	7.单双标签的寓意讲解
	8.ctrl+c   ctrl+s  ctrl+v   F5刷新
	课后总结：
第三课：
	前情提要：
	都是文字相关的标签处理
	
	行内元素,每个块级标签都会独占一行,可以设置宽高
	块内元素,按行逐一显示,前后不会自动换行,多个行级标签可以在一行显示,宽度由装载的内容决定,高度上下边距设置无效
	
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
	前情提要：
	编辑器
	创建目录结构
	常用属性
		id class name value type
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
	前情提要：
	<table>	定义表格
	<caption>	定义表格标题。
	<th>	定义表格中的表头单元格。
	<tr>	定义表格中的行。
	<td>	定义表格中的单元。
	<div>	定义文档中的节。
	<span>	定义文档中的节。
	课后总结：
第六课：
	前情提要：
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
	前情提要：
	css样式就是设置标签的属性
		标签属性
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
	font-size	规定文本的字体尺寸。	1默认16px;设置的是字体的高
	font-style	规定文本的字体样式。	1italic
	font-weight	规定字体的粗细。
	
	color	设置文本的颜色。	1
		颜色的三种方式
		
		透明色:transparent
		
			土鳖式(英文单词)
			颜色代码
			颜色函数rgb(0-255,0-255,0-255)
	
	letter-spacing	设置字符间距。	1
	line-height	设置行高。	1
		单行文本垂直居中,line-height=height让文本高度等于行高
	text-align	规定文本的水平对齐方式。
	text-indent: 2em 首行缩进(两字体)
	
	text-decoration: line-through;none;underline;overline
	
	cursor:pointer;help;copy;改变鼠标样式
	
	opacity	规定元素的不透明级别。
	background	在一个声明中设置所有的背景属性。	1
	background-color	设置元素的背景颜色。	1
	background-image	设置元素的背景图像。	1
	
	课后总结：
第八课：
	前情提要：
	display
	行内元素  inline
		内容决定元素所占位置
		不可以通过css改变宽高
	块内元素 block
		独占一行
		可以通过css改变宽高
	行级块元素  img
		内容决定大小
		可以通过css改变宽高
	盒子模型  margin-border-padding
	
	选择器
		并列选择器(标签在前)div.demo
		element,element	div,p	选择所有 <div> 元素和所有 <p> 元素。	1分组选择器
		element element	div p	选择 <div> 元素内部的所有 <p> 元素。	1父子选择器
		element>element	div>p	选择父元素为 <div> 元素的所有 <p> 元素。	2直接子元素选择器
		element+element	div+p	选择紧接在 <div> 元素之后的所有 <p> 元素。	2
		[attribute]	[target]	选择带有 target 属性所有元素。	2
		[attribute=value]	[target=_blank]	选择 target="_blank" 的所有元素。	2
		[attribute~=value]	[title~=flower]	选择 title 属性包含单词 "flower" 的所有元素。	2
		[attribute|=value]	[lang|=en]	选择 lang 属性值以 "en" 开头的所有元素。
	
	width: 宽
	height:长
	
	top
	bottom
	left
	right
	
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
	前情提要：
	选择器
		:hover	a:hover	选择鼠标指针位于其上的链接。	1
		:focus	input:focus	选择获得焦点的 input 元素。	2
		:first-letter	p:first-letter	选择每个 <p> 元素的首字母。	1
		:first-line	p:first-line	选择每个 <p> 元素的首行。	1
		:first-child	p:first-child	选择属于父元素的第一个子元素的每个 <p> 元素。	2
		:before	p:before	在每个 <p> 元素的内容之前插入内容。	2
		:after	p:after	在每个 <p> 元素的内容之后插入内容。	2
		:lang(language)	p:lang(it)	选择带有以 "it" 开头的 lang 属性值的每个 <p> 元素。	2
		element1~element2	p~ul	选择前面有 <p> 元素的每个 <ul> 元素。	3
		[attribute^=value]	a[src^="https"]	选择其 src 属性值以 "https" 开头的每个 <a> 元素。	3
		[attribute$=value]	a[src$=".pdf"]	选择其 src 属性以 ".pdf" 结尾的所有 <a> 元素。	3
		[attribute*=value]	a[src*="abc"]	选择其 src 属性中包含 "abc" 子串的每个 <a> 元素。	3
		:first-of-type	p:first-of-type	选择属于其父元素的首个 <p> 元素的每个 <p> 元素。	3
		:last-of-type	p:last-of-type	选择属于其父元素的最后 <p> 元素的每个 <p> 元素。	3
		:only-of-type	p:only-of-type	选择属于其父元素唯一的 <p> 元素的每个 <p> 元素。	3
		:only-child	p:only-child	选择属于其父元素的唯一子元素的每个 <p> 元素。	3
		:nth-child(n)	p:nth-child(2)	选择属于其父元素的第二个子元素的每个 <p> 元素。	3
		:nth-last-child(n)	p:nth-last-child(2)	同上，从最后一个子元素开始计数。	3
		:nth-of-type(n)	p:nth-of-type(2)	选择属于其父元素第二个 <p> 元素的每个 <p> 元素。	3
		:nth-last-of-type(n)	p:nth-last-of-type(2)	同上，但是从最后一个子元素开始计数。	3
		:last-child	p:last-child	选择属于其父元素最后一个子元素每个 <p> 元素。	3
		:root	:root	选择文档的根元素。	3
		:empty	p:empty	选择没有子元素的每个 <p> 元素（包括文本节点）。	3
		:target	#news:target	选择当前活动的 #news 元素。	3
		:enabled	input:enabled	选择每个启用的 <input> 元素。	3
		:disabled	input:disabled	选择每个禁用的 <input> 元素	3
		:checked	input:checked	选择每个被选中的 <input> 元素。	3
		:not(selector)	:not(p)	选择非 <p> 元素的每个元素。	3
		::selection	::selection	选择被用户选取的元素部分。
			
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
	前情提要：
	position定位
	图片旋转
	float
		作用:将页面元素浮动起来,使其能够向左或者向右排列(多列同行展示)
		应用:
			实现页面中布局的左右排版
			实现图文环绕(浮动的图片和默认文档流中的文字的效果实现)
		值: left  right  none
		原理:
			浮动元素将脱离默认的文档流,不漂浮在默认文档流之上
			浮动的元素会向左或向右移动,直到它的外边缘碰到父级元素或这个元素之前的另一个浮动元素的边框为止
		效果:
			元素float后,行元素会有块级元素的属性(即可以设置宽 高)
		特点:
			尽管浮动元素脱离了默认文档流,但是仍然会影响到默认文档流中的盒子里装的"内容"(文字),这些"内容"会给浮动元素留出占位
	
	clear:清除浮动
		值:
			both  left  right  none
		清除最最近的一个浮动元素
		实际应用:解决网页中的塌陷问题
			塌陷:如果父元素只包含浮动元素,那么如果父元素没有设置高度,则父元素的高度会塌缩为0
		解决塌陷的办法:
			1.创建一个用来清除浮动的CSS样式类(.clearfix)
			2.针对包裹的全是浮动元素的父元素使用(.clearfix)
			.clearfix{zoom:1;}//zoom是IE浏览器专有属性,为了兼容IE低版本的浏览器
			.clearfix:after{//:after伪对象选择符--在这个对象被浏览器渲染后添加一定的内容
				content:".";//content属性:添加的内容写在content属性中,这个属性是专门配合伪对象使用的,必须要写,就算内容为空也要写
				display:block;//将添加的内容设置为块元素
				visibility:hidden;//visibility:可视化属性,控制元素是否可见(隐身衣),元素无论是否可见,都会保留其物理空间,(与display:none比较,display:none是消除物理空间)
				height:0;//添加的内容高度设置为0
				clear:both;}//消除浮动
				
	主流网站布局方式
		静态布局static   入门
		响应式布局responsive
		弹性布局flexbox(css3布局方式)
	
	课后总结：
第十一课：
	前情提要：
	照片墙制作
	课后总结：
第十二课：
	前情提要：
	照片墙制作
	课后总结：
第十三课：
	前情提要：
	js的本质就是改变标签的属性
	javascript是当下最流行的编程语言
	JavaScript于1995年由网景公司的布兰登  艾奇(Brendan Eich)设计而成的,因为对js的支持,网景公司的浏览器Navigator一直占领着浏览器市场的绝大部分份额,而后因为微软公司的
	IE浏览器因为也慢慢支持的js语言,所以才慢慢打败网景的Navigator浏览器,主宰浏览器市场.
	js特点
		跨平台
		事件驱动
		页面进行交互
		与服务器进行交互
	js的引入?
		行间
		内嵌
		外部链接
	js简单实例	
		点击按钮,改变div的宽 高 背景颜色和内容(into_javascript.html)
	js注释
		注释的作用:1.添加代码说明,提高代码的易读性2.使代码无效
		<!--html的注释-->
		/*
		 *css的注释
		 */
		//单行注释
		/*
		 *多行注释
		 */
	课后总结：
第十四课：
	前情提要：
	课后总结：
第十五课：
	前情提要：
	课后总结：
第十六课：
	前情提要：
	课后总结：
第十七课：
	前情提要：
	课后总结：
第十八课：
	前情提要：
	课后总结：
第十九课：
	前情提要：
	课后总结：
第二十课：
	前情提要：
	课后总结：
第二十一课：
	前情提要：
	课后总结：
第二十二课：
	前情提要：
	课后总结：
第二十三课：
	前情提要：
	课后总结：
第二十四课：
	前情提要：
	课后总结：
第二十五课：
	前情提要：
	课后总结：
第二十六课：
	前情提要：
	课后总结：
第二十七课：
	前情提要：
	课后总结：
第二十八课：
	前情提要：
	课后总结：
第二十九课：
	前情提要：
	课后总结：
第三十课：
	前情提要：
	课后总结：
	
	
	
属性,在js之前加上属性讲解