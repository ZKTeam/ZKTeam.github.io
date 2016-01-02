---
layout: default
title: ZKTeam 专业 App 定制开发
---
<html>
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
			});
	    </script>
	</head>
<body>
		<div class="banner">
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
						<p>iOS 与 Android资深创作团队，提供个性化、全方位服务。</p>
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

		<div class="features">
			<ul class="wrap">
				<li class="browser">
					<b>App 需求分析</b>
					<p>从用户角度出发，提供闭环逻辑思维。</p>
				</li>

				<li class="keyboard">
					<b>App 界面设计</b>
					<p>简单直接的UI设计，让界面更有视觉冲击。</p>
				</li>

				<li class="height">
					<b>App 软件开发</b>
					<p>研发、上线、售后服务，适应各尺寸机型。</p>
				</li>

				<li class="responsive">
					<b>待定</b>
					<p>如今哪个网站还不支持响应式布局就已经非常OUT了。</p>
				</li>
			</ul>
		</div>

		<div id="howto" class="how wrap">
			<h2>合作流程</h2>
			<ol>
				<li>
					<div>
						<h3>引入jQuery 和 Unslider </h3>
						<p>To use Unslider, you’ll need to make sure both the Unslider and jQuery scripts are included. If you’ve already got jQuery (you can test by opening your JavaScript console and typing <code>!!window.jQuery</code> — if it says <code>true</code>, you have jQuery), you don’t need to add the first line.</p>
					</div>
				</li>

				<li>
					<div>
						<h3>准备HTML代码</h3>
						<p>Unslider doesn’t need any really awkward markup. In fact, all you need is a <code>div</code> and an unordered list. An example of some Unslider-friendly HTML is on the right.</p>
						<p>You can add as many slides as you want: the example on the right just has three for the sake of brevity, but Unslider won’t work properly with one slide (but then it’s just a box).</p>
					</div>
				</li>

				<li>
					<div>
						<h3>Plug it all together</h3>
						<p>We’ve been through so much together, and I’m pleased to say the finish line is near. Our journey is almost over, just one more thing left to do. The JavaScript is on the right (make sure to put it in a <code>script</code> tag, and change <code>.banner</code> to whatever your slider’s element is).</p>
					</div>
				</li>
			</ol>
		</div>

		<div class="contact">
			<div class="wrap">
				<h2>联系我们</h2>
				<p>电话：18610513559、18510509294
				<br />
				QQ：573065858、1020304029</p>				
			</div>
		</div>

		<div class="wrap footer">
			<p>&copy;&nbsp;Copyright 2014 - {{site.time | date:"%Y"}}</p>
		</div>

</body>
</html>