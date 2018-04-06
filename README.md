# CSS Box Style Code Along

## Overview

In this code along exercise we will apply some CSS box styles such as
background images, gradients, drop shadows, and borders. All the files you need
to follow along are provided and opening this code along on the in-browser IDE
will fork and clone down a copy for you, but if you would like to continue
working from your personal `exceptional-realty` repository:

```
git clone https://github.com/<your_username_here>/exceptional-realty
cd exceptional-realty
```

We'll work on a new branch in this code along, so go ahead and create a branch
called `navbar-and-background-styles`.

**Note:** If you are using the in-browser IDE, you won't be able to open images directly from the directory tree.  However, you can still reference the images in your HTML and will be able to see them if you run `httpserver` in your IDE terminal to temporarily host your `index.html`.

The gradient code that is copied and pasted in the exercise is located at the
bottom of this lesson.

<iframe width="640" height="480" src="//www.youtube.com/embed/Y4El1I-hagQ?rel=0&controls=1&showinfo=1" frameborder="0" allowfullscreen></iframe>

Don't forget to commit and push up your work!

### Gradient Code Snippets

```css
/* LIGHT-FADE */

background: #efefef; /* Old browsers */
background: -moz-linear-gradient(
  top,
  #efefef 0%,
  #ffffff 24%,
  #ffffff 68%,
  #dddddd 100%
); /* FF3.6+ */
background: -webkit-gradient(
  linear,
  left top,
  left bottom,
  color-stop(0%, #efefef),
  color-stop(24%, #ffffff),
  color-stop(68%, #ffffff),
  color-stop(100%, #dddddd)
); /* Chrome,Safari4+ */
background: -webkit-linear-gradient(
  top,
  #efefef 0%,
  #ffffff 24%,
  #ffffff 68%,
  #dddddd 100%
); /* Chrome10+,Safari5.1+ */
background: -o-linear-gradient(
  top,
  #efefef 0%,
  #ffffff 24%,
  #ffffff 68%,
  #dddddd 100%
); /* Opera 11.10+ */
background: -ms-linear-gradient(
  top,
  #efefef 0%,
  #ffffff 24%,
  #ffffff 68%,
  #dddddd 100%
); /* IE10+ */
background: linear-gradient(
  to bottom,
  #efefef 0%,
  #ffffff 24%,
  #ffffff 68%,
  #dddddd 100%
); /* W3C */
filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#efefef", endColorstr="#dddddd", GradientType=0); /* IE6-9 */
```

```css
/* MEDIUM-FADE */

background: rgb(229, 229, 229); /* Old browsers */
background: -moz-linear-gradient(
  top,
  rgba(229, 229, 229, 1) 0%,
  rgba(255, 255, 255, 1) 99%
); /* FF3.6+ */
background: -webkit-gradient(
  linear,
  left top,
  left bottom,
  color-stop(0%, rgba(229, 229, 229, 1)),
  color-stop(99%, rgba(255, 255, 255, 1))
); /* Chrome,Safari4+ */
background: -webkit-linear-gradient(
  top,
  rgba(229, 229, 229, 1) 0%,
  rgba(255, 255, 255, 1) 99%
); /* Chrome10+,Safari5.1+ */
background: -o-linear-gradient(
  top,
  rgba(229, 229, 229, 1) 0%,
  rgba(255, 255, 255, 1) 99%
); /* Opera 11.10+ */
background: -ms-linear-gradient(
  top,
  rgba(229, 229, 229, 1) 0%,
  rgba(255, 255, 255, 1) 99%
); /* IE10+ */
background: linear-gradient(
  to bottom,
  rgba(229, 229, 229, 1) 0%,
  rgba(255, 255, 255, 1) 99%
); /* W3C */
```

```css
/* NAVBAR-HOVER */

background: rgb(0, 0, 0); /* Old browsers */
background: -moz-linear-gradient(
  top,
  rgba(0, 0, 0, 1) 0%,
  rgba(71, 71, 71, 1) 28%,
  rgba(81, 81, 81, 1) 35%,
  rgba(71, 71, 71, 1) 72%,
  rgba(43, 43, 43, 1) 87%,
  rgba(28, 28, 28, 1) 91%,
  rgba(0, 0, 0, 1) 100%
); /* FF3.6+ */
background: -webkit-gradient(
  linear,
  left top,
  left bottom,
  color-stop(0%, rgba(0, 0, 0, 1)),
  color-stop(28%, rgba(71, 71, 71, 1)),
  color-stop(35%, rgba(81, 81, 81, 1)),
  color-stop(72%, rgba(71, 71, 71, 1)),
  color-stop(87%, rgba(43, 43, 43, 1)),
  color-stop(91%, rgba(28, 28, 28, 1)),
  color-stop(100%, rgba(0, 0, 0, 1))
); /* Chrome,Safari4+ */
background: -webkit-linear-gradient(
  top,
  rgba(0, 0, 0, 1) 0%,
  rgba(71, 71, 71, 1) 28%,
  rgba(81, 81, 81, 1) 35%,
  rgba(71, 71, 71, 1) 72%,
  rgba(43, 43, 43, 1) 87%,
  rgba(28, 28, 28, 1) 91%,
  rgba(0, 0, 0, 1) 100%
); /* Chrome10+,Safari5.1+ */
background: -o-linear-gradient(
  top,
  rgba(0, 0, 0, 1) 0%,
  rgba(71, 71, 71, 1) 28%,
  rgba(81, 81, 81, 1) 35%,
  rgba(71, 71, 71, 1) 72%,
  rgba(43, 43, 43, 1) 87%,
  rgba(28, 28, 28, 1) 91%,
  rgba(0, 0, 0, 1) 100%
); /* Opera 11.10+ */
background: -ms-linear-gradient(
  top,
  rgba(0, 0, 0, 1) 0%,
  rgba(71, 71, 71, 1) 28%,
  rgba(81, 81, 81, 1) 35%,
  rgba(71, 71, 71, 1) 72%,
  rgba(43, 43, 43, 1) 87%,
  rgba(28, 28, 28, 1) 91%,
  rgba(0, 0, 0, 1) 100%
); /* IE10+ */
background: linear-gradient(
  to bottom,
  rgba(0, 0, 0, 1) 0%,
  rgba(71, 71, 71, 1) 28%,
  rgba(81, 81, 81, 1) 35%,
  rgba(71, 71, 71, 1) 72%,
  rgba(43, 43, 43, 1) 87%,
  rgba(28, 28, 28, 1) 91%,
  rgba(0, 0, 0, 1) 100%
); /* W3C */
```

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/fe-code-along-ex-5' title='Overview'>Overview</a> on Learn.co and start learning to code for free.</p>
