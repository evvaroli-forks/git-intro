# Intro

Usage of this template

-----
<!-- .slide: class="left" -->
## What can I do?

- Everything that reaveal.js can do see [reveal.js](https://revealjs.com)
- Everything you are used to do in markdown
- `-----` ... horizontal slide
- `---`... vertical slide
- Note (just for speaker) with `Note:`
- Activate speaker view with 's' (allow pop up!)
- Hide presentation with '.' or 'b'
- Zoom with `Alt+Click` (win) or `Ctrl+Click` (nix)

> Citation as you are used to in markdown...

Note: you cant see me!

-----
<!-- .slide: class="left" -->
## Some specifics - HTML

- Insert html code to spice things up
  - left orientation instead of centering:

      put `<!-- .slide: class="left" -->` to start of slide

  - include external files directly with:

      `<!--#include file="dir/filename" -->`

      (look 'down' for an example)

---
<!-- .slide: class="left" -->
## External file usage sample

This loads the java file `Hello.java` from subfolder `src`

```java
<!--#include file="src/Hello.java" -->
```

You found the errors? Good for you!

-----
<!-- .slide: class="left" -->
## Math style with mathjax

Inline: $f(x)=\frac{a}{b}$...

Own line:
$$f(x)=\frac{a}{b}$$

-----

## FIN

the end...
