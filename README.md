=============================

Stylus Mixins

Version 1.0

August 21, 2013

Created by Dinh Nguyen

Original: www.dinhnguyen.info

License: MIT/GPL

https://github.com/dinhnguyen/stylus-mixins.git

Stylus is a revolutionary new language, providing an efficient, dynamic, and expressive way to generate CSS. Supporting both an indented syntax and regular CSS style.

http://learnboost.github.io/stylus/

=============================

Usage is simple:

1) Creat your stylus file "file_name.styl"

2) Include mixins file on top of your stylus files

```css
@import "mixins.styl";
```

3) Start write your stylus and use mixins, like this

```css
h1
	dis inline-block
	wh 251px 200px
	bg url('../text-logo.png') no-repeat
	tex-i -9999px
	fo-s 0.0001em
```

it will compline to this 

```css
h1 {
	display: inline-block;
	width: 251px;
	height: 200px;
	background:url("../text-logo.png") no-repeat;
	text-indent: -9999px;
	font-size: .0001em
	}
```

4) Enjoy its :)

=============================
Change Notes:
=============================

v1.0
	- First commit


