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

---

__a__

    <a href="$1">$2</a>

__com__

    <!-- $1 -->

__fig__

    <figure>
        <img src="$1" alt="$2">
        <figcaption>$3</figcaption>
    </figure>

__html__

    <!doctype html>
    <html>
        <head>
            <meta charset="utf-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
            <meta name="description" content="$1">
            <meta name="viewport" content="width=device-width, initial-scale=1">
            <title>$2</title>
            <link rel="stylesheet" href="css/main.css">
        </head>
        <body>
            $3
            <script src="js/main.js"></script>
        </body>
    </html>

__img__

    <img src="$1" alt="$2">

__jquery__

    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
    <script>window.jQuery || document.write('<script src="js/vendor/jquery-1.8.3.min.js"><\/script>')</script>

__lin__

    <link rel="stylesheet" href="$1">

__lorem__

    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
    non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

__nav__

For when using `inline-block`.

    <nav class="main-nav">
        <ul>
            <li><a href="#">$1</a></li><!--
         --><li><a href="#">$2</a></li><!--
         --><li><a href="#">$3</a></li><!--
         --><li><a href="#">$4</a></li>
        </ul>
    </nav>

__nav2__

    <nav class="main-nav">
        <ul>
            <li>
                <a href="#">$1</a>
            </li>
            <li>
                <a href="#">$2</a>
            </li>
            <li>
                <a href="#">$3</a>
            </li>
            <li>
                <a href="#">$4</a>
            </li>
        </ul>
    </nav>

__ol__

    <ol>
        <li>$1</li>
        <li>$2</li>
        <li>$3</li>
        <li>$4</li>
    </ol>

__scr__

    <script src="$1"></script>

__ul__

    <ul>
        <li>$1</li>
        <li>$2</li>
        <li>$3</li>
        <li>$4</li>
    </ul>
