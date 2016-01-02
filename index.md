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
		<div class="banner">
			<ul>
				<li style="background-image: url('img/sunset.jpg');">
					<div class="inner">
						<h1>The jQuery slider that just slides.</h1>
						<p>就是这个不到3kb的插件！没有奇特的特效或无用的标签。</p>

						<a class="btn" href="#download">下载</a>
					</div>
				</li>

				<li style="background-image: url('img/wood.jpg');">
					<div class="inner">
						<h1>Fluid, flexible, fantastically minimal.</h1>
						<p>Use any HTML in your slides, extend with CSS. You have full control.</p>

						<a class="btn" href="#download">下载</a>
					</div>
				</li>

				<li style="background-image: url('img/subway.jpg');">
					<div class="inner">
						<h1>开源</h1>
						<p>Unslider的所有源码都托管在GitHub上。</p>

						<a class="btn" href="//github.com/idiot/unslider">参与</a>
					</div>
				</li>

				<li style="background-image: url('img/shop.jpg');">
					<div class="inner">
						<h1>Uh, that’s about it.</h1>
						<p>I just wanted to show you another slide.</p>

						<a class="btn" href="#download">下载</a>
					</div>
				</li>
			</ul>
		</div>

		<div class="features">
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

		<div id="howto" class="how wrap">
			<h2>如何使用Unslider</h2>

			<ol>
				<li>
					<div>
						<h3>引入jQuery 和 Unslider </h3>
						<p>To use Unslider, you’ll need to make sure both the Unslider and jQuery scripts are included. If you’ve already got jQuery (you can test by opening your JavaScript console and typing <code>!!window.jQuery</code> — if it says <code>true</code>, you have jQuery), you don’t need to add the first line.</p>
					</div>

					<pre>&lt;script src="//code.jquery.com/jquery-latest.min.js"&gt;&lt;/script&gt;
&lt;script src="//unslider.com/unslider.js"&gt;&lt;/script&gt;
</pre>
				</li>

				<li>
					<div>
						<h3>准备HTML代码</h3>
						<p>Unslider doesn’t need any really awkward markup. In fact, all you need is a <code>div</code> and an unordered list. An example of some Unslider-friendly HTML is on the right.</p>
						<p>You can add as many slides as you want: the example on the right just has three for the sake of brevity, but Unslider won’t work properly with one slide (but then it’s just a box).</p>
					</div>

					<pre>&lt;div class=&quot;banner&quot;&gt;
    &lt;ul&gt;
        &lt;li&gt;This is a slide.&lt;/li&gt;
        &lt;li&gt;This is another slide.&lt;/li&gt;
        &lt;li&gt;This is a final slide.&lt;/li&gt;
    &lt;/ul&gt;
&lt;/div&gt;</pre>
				</li>

				<li>
					<div>
						<h3>Make it pretty</h3>
						<p>You can change, add, and remove as much CSS per slide as you want, but there <i>is</i> a barebones style required by Unslider. It’s on the right (change the class name where .banner is the name of your slider).</p>
					</div>

					<pre>.banner { position: relative; overflow: auto; }
    .banner li { list-style: none; }
        .banner ul li { float: left; }</pre>
				</li>

				<li>
					<div>
						<h3>Plug it all together</h3>
						<p>We’ve been through so much together, and I’m pleased to say the finish line is near. Our journey is almost over, just one more thing left to do. The JavaScript is on the right (make sure to put it in a <code>script</code> tag, and change <code>.banner</code> to whatever your slider’s element is).</p>
					</div>

					<pre>$(function() {
    $('.banner').unslider();
});</pre>
				</li>
			</ol>
		</div>

		<div id="options" class="options">
			<div class="wrap">
				<h2>参数</h2>
				<p>Although it’s lightweight, Unslider comes with a range of options to customise your slider. Here’s the default options provided. You can add, remove, or completely skip out the options object. It’s up to you.</p>

				<pre>$('.banner').unslider({
	speed: 500,               <span>//  The speed to animate each slide (in milliseconds)</span>
	delay: 3000,              <span>//  The delay between slide animations (in milliseconds)</span>
	complete: function() {},  <span>//  A function that gets called after every slide animation</span>
	keys: true,               <span>//  Enable keyboard (left, right) arrow shortcuts</span>
	dots: true,               <span>//  Display dot navigation</span>
	fluid: false              <span>//  Support responsive design. May break non-responsive designs</span>
});</pre>
<br><br><br>
				<h2 id="touch">支持触摸屏</h2>
				<p>If you want to add mobile/touch/swipe/whatever support to Unslider, you’ll need to include the <a href="http://stephband.info/jquery.event.swipe/">jQuery.event.swipe</a> plugin, then it’ll work out the box. Easy!</p>

<br><br><br>

				<h2 id="prev-next">添加向前(previous)/向后（next）链接</h2>
				<p>A feature that’s often requested in Unslider, but isn’t included in-the-box, is previous/next links. Luckily, they’re easy enough to add with a little script, which utilises Unslider’s <a href="#methods">methods</a>.</p>

				<pre><span>&lt;!-- The HTML --&gt;</span>
&lt;a href="#" class="unslider-arrow prev"&gt;Previous slide&lt;/a&gt;
&lt;a href="#" class="unslider-arrow next"&gt;Next slide&lt;/a&gt;

<span>&lt;!-- And the JavaScript --&gt;</span>
&lt;script&gt;
    var unslider = $('.banner').unslider();

    $('.unslider-arrow').click(function() {
        var fn = this.className.split(' ')[1];

        <span>//  Either do unslider.data('unslider').next() or .prev() depending on the className</span>
        unslider.data('unslider')[fn]();
    });
&lt;/script&gt;
</pre>

<br><br><br>
				<h2 id="methods">存取Unslider的属性</h2>
				<p>Using jQuery’s wonderful <code>data</code> method, you can access and manually override any methods. Here’s a list of what you can do:</p>

				<pre>var slidey = $('.banner').unslider(),
    data = slidey.data('unslider');

<span>//  Start Unslider</span>
data.start();

<span>//  Pause Unslider</span>
data.stop();

<span>//  Move to a slide index, with optional callback</span>
data.move(2, function() {});
<span>//  data.move(0);</span>

<span>//  Manually enable keyboard shortcuts</span>
data.keys();

<span>//  Move to the next slide (or the first slide if there isn't one)</span>
data.next();

<span>//  Move to the previous slide (or the last slide if there isn't one)</span>
data.prev();

<span>//  Append the navigation dots manually</span>
data.dots();</pre>
			</div>
		</div>

		<div id="download" class="wrap footer">
			<a class="btn" href="https://github.com/idiot/unslider/blob/master/src/unslider.min.js">下载 <span>压缩文件 (2.6k)</span></a>
			<a class="btn" href="https://github.com/idiot/unslider/blob/master/src/unslider.js">下载 <span>源码 (5.1k)</span></a>
			<br>
			<a href="//twitter.com/idiot">@idiot</a> &mdash; <a href="//github.com/idiot/unslider">Github</a>

			<p>Unslider由<a href="http://www.bootcss.com/">Bootstrap中文网</a>翻译整理</p>
		</div>

</body>