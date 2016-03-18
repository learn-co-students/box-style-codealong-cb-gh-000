# CSS Box Style Code Along

## Overview

In this code along exercise we will apply some CSS box styles such as background images, gradients, drop shadows, and  borders.

## Steps

1. Fork this repository.
2. Clone your fork.
3. cd into the folder for this lab.
4. Code along with the included video below.

The gradient code that is copied and pasted in the exercise is located at the bottom of this lesson.

<iframe width="100%" height="720" src="//www.youtube.com/embed/Y4El1I-hagQ?rel=0&controls=1&showinfo=1" frameborder="0" allowfullscreen></iframe>

### Gradient Code Snippets

```css
/* LIGHT-FADE */

background: #efefef; /* Old browsers */
background: -moz-linear-gradient(top,  #efefef 0%, #ffffff 24%, #ffffff 68%, #dddddd 100%); /* FF3.6+ */
background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#efefef), color-stop(24%,#ffffff), color-stop(68%,#ffffff), color-stop(100%,#dddddd)); /* Chrome,Safari4+ */
background: -webkit-linear-gradient(top,  #efefef 0%,#ffffff 24%,#ffffff 68%,#dddddd 100%); /* Chrome10+,Safari5.1+ */
background: -o-linear-gradient(top,  #efefef 0%,#ffffff 24%,#ffffff 68%,#dddddd 100%); /* Opera 11.10+ */
background: -ms-linear-gradient(top,  #efefef 0%,#ffffff 24%,#ffffff 68%,#dddddd 100%); /* IE10+ */
background: linear-gradient(to bottom,  #efefef 0%,#ffffff 24%,#ffffff 68%,#dddddd 100%); /* W3C */
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#efefef', endColorstr='#dddddd',GradientType=0 ); /* IE6-9 */
```

```css
/* MEDIUM-FADE */

background: rgb(229,229,229); /* Old browsers */
background: -moz-linear-gradient(top,  rgba(229,229,229,1) 0%, rgba(255,255,255,1) 99%); /* FF3.6+ */
background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(229,229,229,1)), color-stop(99%,rgba(255,255,255,1))); /* Chrome,Safari4+ */
background: -webkit-linear-gradient(top,  rgba(229,229,229,1) 0%,rgba(255,255,255,1) 99%); /* Chrome10+,Safari5.1+ */
background: -o-linear-gradient(top,  rgba(229,229,229,1) 0%,rgba(255,255,255,1) 99%); /* Opera 11.10+ */
background: -ms-linear-gradient(top,  rgba(229,229,229,1) 0%,rgba(255,255,255,1) 99%); /* IE10+ */
background: linear-gradient(to bottom,  rgba(229,229,229,1) 0%,rgba(255,255,255,1) 99%); /* W3C */
```

```css
/* NAVBAR-HOVER */

background: rgb(0,0,0); /* Old browsers */
background: -moz-linear-gradient(top,  rgba(0,0,0,1) 0%, rgba(71,71,71,1) 28%, rgba(81,81,81,1) 35%, rgba(71,71,71,1) 72%, rgba(43,43,43,1) 87%, rgba(28,28,28,1) 91%, rgba(0,0,0,1) 100%); /* FF3.6+ */
background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(0,0,0,1)), color-stop(28%,rgba(71,71,71,1)), color-stop(35%,rgba(81,81,81,1)), color-stop(72%,rgba(71,71,71,1)), color-stop(87%,rgba(43,43,43,1)), color-stop(91%,rgba(28,28,28,1)), color-stop(100%,rgba(0,0,0,1))); /* Chrome,Safari4+ */
background: -webkit-linear-gradient(top,  rgba(0,0,0,1) 0%,rgba(71,71,71,1) 28%,rgba(81,81,81,1) 35%,rgba(71,71,71,1) 72%,rgba(43,43,43,1) 87%,rgba(28,28,28,1) 91%,rgba(0,0,0,1) 100%); /* Chrome10+,Safari5.1+ */
background: -o-linear-gradient(top,  rgba(0,0,0,1) 0%,rgba(71,71,71,1) 28%,rgba(81,81,81,1) 35%,rgba(71,71,71,1) 72%,rgba(43,43,43,1) 87%,rgba(28,28,28,1) 91%,rgba(0,0,0,1) 100%); /* Opera 11.10+ */
background: -ms-linear-gradient(top,  rgba(0,0,0,1) 0%,rgba(71,71,71,1) 28%,rgba(81,81,81,1) 35%,rgba(71,71,71,1) 72%,rgba(43,43,43,1) 87%,rgba(28,28,28,1) 91%,rgba(0,0,0,1) 100%); /* IE10+ */
background: linear-gradient(to bottom,  rgba(0,0,0,1) 0%,rgba(71,71,71,1) 28%,rgba(81,81,81,1) 35%,rgba(71,71,71,1) 72%,rgba(43,43,43,1) 87%,rgba(28,28,28,1) 91%,rgba(0,0,0,1) 100%); /* W3C */
```

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/fe-code-along-ex-5' title='Overview'>Overview</a> on Learn.co and start learning to code for free.</p>
