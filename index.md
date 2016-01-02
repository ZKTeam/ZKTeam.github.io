---
layout: default
title: ZKTeam 专业 App 定制开发
---
<head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>{{ page.title }}</title>
	<link rel="fluid-icon" href="/fluidicon.png" />
    <link rel="apple-touch-icon" sizes="57x57" href="/images/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="114x114" href="/images/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="72x72" href="/images/apple-touch-icon-144.png" />
    <link rel="apple-touch-icon" sizes="144x144" href="/images/apple-touch-icon-144.png" />
    <link rel="icon" type="image/x-icon" href="/images/favicon.ico" />
    <link rel="stylesheet" href="//cdn.bootcss.com/bootstrap/3.3.5/css/bootstrap.min.css">
    <link rel="stylesheet" href="/css/main.css" />
    <link rel="stylesheet" href="/css/index.css" />
    <script src="//cdn.bootcss.com/jquery/1.11.3/jquery.min.js"></script>
    <script src="//cdn.bootcss.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
    <script src="//unslider.com/unslider.js"></script>
    <script type="text/javascript">
    	$(function() {
		    $('.banner').unslider({
				speed: 500,               //  The speed to animate each slide (in milliseconds)
				delay: 3000,              //  The delay between slide animations (in milliseconds)
				complete: function() {},  //  A function that gets called after every slide animation
				keys: true,               //  Enable keyboard (left, right) arrow shortcuts
				dots: true,               //  Display dot navigation
				fluid: true              //  Support responsive design. May break non-responsive designs
			});
			// $("#header").headroom();
		});
    </script>
</head>
<body>
	<!-- 导航 -->    
	<nav class="navbar navbar-default navbar-fixed-top nav">
		<div class="container-fluid">
			<div class="navbar-header">
				<a class="navbar-brand" href="#">ZKTeam 给你想要的</a>
			</div>
			<div class="collapse navbar-collapse">
				<ul class="nav navbar-nav navbar-right">
					<li><a href="#banner">首页</a></li>
					<li><a href="#service">服务</a></li>
					<li><a href="#case">案例</a></li>
					<li><a href="#contact">联系</a></li>
				</ul>
			</div>
		</div>
	</nav>
	<!-- 轮播 -->
	<div id="banner" class="banner">
		<ul>
			<li style="background-image: url('http://www.bootcss.com/p/unslider/img/sunset.jpg');">
				<div class="inner">
					<h1>专业技术</h1>
					<p>APP专业制作团队 ：只要说清你的需求，就给你想要的。</p>
				</div>
			</li>
			<li style="background-image: url('http://www.bootcss.com/p/unslider/img/wood.jpg');">
				<div class="inner">
					<h1>全方位服务</h1>
					<p>iOS 与 Android 资深创作团队，提供个性化、全方位服务。</p>
				</div>
			</li>
			<li style="background-image: url('http://www.bootcss.com/p/unslider/img/subway.jpg');">
				<div class="inner">
					<h1>极致体验</h1>
					<p>完美用户体验，才是制胜王道。</p>
				</div>
			</li>
		</ul>
	</div>
	<div class="">
		<div class="service">
				<ul class="wrap">
					<li class="browser">
						<b>跨浏览器</b>
						<p>Unslider已经在所有最新的浏览器上测试过了，并且对那些老旧的浏览器也能很出色的降级处理。</p>
					</li>
					<li class="keyboard">
						<b>支持键盘导航</b>
						<p>如果需要，可以加入键盘方向键导航。试一试左右方向键吧！</p>
					</li>
					<li class="height">
						<b>自动调整高度</b>
						<p>并不是每个幻灯片都很规范，Unslider能够自动调整高度。</p>
					</li>
					<li class="responsive">
						<b>Yep，他还支持响应式布局</b>
						<p>如今哪个网站还不支持响应式布局就已经非常OUT了。Unslider帮你轻松搞定！</p>
					</li>
				</ul>
			</div>
		{% include service.md %}
		{% include case.md %}
		{% include contact.md %}
	</div>
	{% include footer.md %}
</body>