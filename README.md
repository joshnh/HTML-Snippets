# Sublime Text 2 HTML Snippets

_A work in progress._

Type the snippet shortcode and then press <kbd>Tab</kbd> to complete the snippet.

The snippets are listed below in alphabetical order. The '$1' indicates the
position of the caret/s. Some snippets have been set up so that pressing Tab
jumps the caret/s to the next predefined spot. It's a little hard to explain,
but any snippet that has a $1/$2/$3/etc. uses this technique.

Feel free to play with, alter, expand, or ruin these snippets as you please. I
only ask that if you come up with an incredibly handy snippet, or simply one
that I have missed, that you let me know (via email, Twitter or GitHub) so that
I can improve these for everybody. Thanks!

__IMPORTANT: If you are also using Emmet, add the following to Emmet's user settings file:__

`"disabled_single_snippets": "html head fig meta nav ol script style ul"`

---

__a__

```html
<a href="$1">$2</a>
```

__comm__

```html
<!-- $1 -->
```

__cond__

```html
<!--[if ${1:lt IE 9}]>
    <link rel="stylesheet" href="${2:css/ie.css">}
<![endif]-->
```

__dummy__

```html
One morning, when Gregor Samsa woke from troubled dreams, he found himself
transformed in his bed into a horrible vermin. He lay on his armour-like back,
and if he lifted his head a little he could see his brown belly, slightly domed
and divided by arches into stiff sections. The bedding was hardly able to cover
it and seemed ready to slide off any moment. His many legs, pitifully thin
compared with the size of the rest of him, waved about helplessly as he looked.
"What's happened to me? " he thought.
```

__fig__

```html
<figure>
    <img src="$1" alt="$2">
    <figcaption>$3</figcaption>
</figure>
```

__ga__

```html
<script>
    var _gaq = [['_setAccount', '${1:UA-XXXXX-X}'], ['_trackPageview']];
    (function(d, t) {
        var g = d.createElement(t),
            s = d.getElementsByTagName(t)[0];
        g.src = '//www.google-analytics.com/ga.js';
        s.parentNode.insertBefore(g, s);
    }(document, 'script'));
</script>
```

__ga2__

```html
<script>
    (function(b,o,i,l,e,r){b.GoogleAnalyticsObject=l;b[l]||(b[l]=
    function(){(b[l].q=b[l].q||[]).push(arguments)});b[l].l=+new Date;
    e=o.createElement(i);r=o.getElementsByTagName(i)[0];
    e.src='//www.google-analytics.com/analytics.js';
    r.parentNode.insertBefore(e,r)}(window,document,'script','ga'));
    ga('create','${1:UA-XXXX-X}');ga('send','pageview');
</script>
```

__head__

```html
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>${2:Untitled}</title>
    <meta name="description" content="$3">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="${4:css/main.css}">
</head>
```

__html__

```html
<!DOCTYPE html>
<html lang="${1:en}">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>${2:Untitled}</title>
        <meta name="description" content="$3">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="${4:css/main.css}">
    </head>
    <body>
        $6
        <script src="${5:js/main.js}"></script>
    </body>
</html>
```

__img__

```html
<img src="$1" alt="$2">
```

__jquery__

```html
<script src="//ajax.googleapis.com/ajax/libs/jquery/${1:1.10.2}/jquery.min.js"></script>
<script>window.jQuery || document.write('<script src="js/vendor/jquery-${1:1.10.2}.min.js"><\/script>')</script>
```

__lorem__

```html
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
culpa qui officia deserunt mollit anim id est laborum.
```

__nav__

For when using `inline-block`.

```html
<nav class="$1">
    <ul>
        <li><a href="#">$2</a></li><!--
     --><li><a href="#">$3</a></li><!--
     --><li><a href="#">$4</a></li><!--
     --><li><a href="#">$5</a></li>
    </ul>
</nav>
```

__nav2__

```html
<nav class="$1">
    <ul>
        <li><a href="#">$2</a></li>
        <li><a href="#">$3</a></li>
        <li><a href="#">$4</a></li>
        <li><a href="#">$5</a></li>
    </ul>
</nav>
```

__ol__

```html
<ol>
    <li>$1</li>
    <li>$2</li>
    <li>$3</li>
    <li>$4</li>
</ol>
```

__script__

```html
<script src="$1"></script>
```

__shiv__

```html
<!--[if lt IE 9]>
    <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
```

__style__

```html
<link rel=stylesheet href="$1">
```

__ul__

```html
<ul>
    <li>$1</li>
    <li>$2</li>
    <li>$3</li>
    <li>$4</li>
</ul>
```

__inp:text__

```html
<input type="text">
```

__inp:tel__

```html
<input type="tel">
```

__inp:radio__

```html
<input type="radio">
```

__inp:check__

```html
<input type="checkbox">
```

__inp:email__

```html
<input type="email">
```

__inp:pass__

```html
<input type="password">
```

__inp:submit__

```html
<input type="submit">
```
