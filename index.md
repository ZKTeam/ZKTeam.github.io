---
layout: default
title: ZKTeam 专业 App 制作开发
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
				fluid: false              //  Support responsive design. May break non-responsive designs
			});
		});
    </script>
</head>
<body>
	<div class="banner">
	    <ul>
	        <li>This is a slide.</li>
	        <li>This is another slide.</li>
	        <li>This is a final slide.</li>
	    </ul>
	</div>
	{% include footer.md %}
</body>