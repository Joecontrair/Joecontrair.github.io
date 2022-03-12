---
layout: Page
---
<html>
    <head>
        <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
        <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
        <script>
        window.MathJax = {
        tex: {
        inlineMath: [['$', '$'], ['\\(', '\\)']]
        }
        };
        </script>
            <center>
            <H1>MathJax:</H1>
            <p> 
            Little Blog talking about how to get MathJax into your HTML File
            </p>
            </center>
    </head>
</html>

# Why
So as one does with any coding or whatever HTMl and markdown counts as, you learn it by taking half of your code and such from google. I think it's called Code Monkeying, so that's pretty neat. 
# How
So in your `<head></head>` you're gonna want to place 
```js 
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script> <br/> 
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
```
This will allow you to use LaTex formatting in your html/markdown files. Now if you wish to change the delimiters that it will use, like to the ones Obsidian uses ($ $), than you can place this in head as well: 
 ```js
        <script>
            window.MathJax = {
            tex: {
            inlineMath: [['$', '$'], ['\\(', '\\)']]
            }
            };
        </script>
```
# Where
So like I said before I've been doing some googling to try and add neat stuff to my website, and getting MathJax was one of those things. Because instead of having to upload a pdf of my proofs and such I can now just upload it directly into here. 
[MathJax](https://www.mathjax.org/#gettingstarted) This here is the MathJax website where I found the actual code fot getting LaTex into my site.
[MathJax/Obsidian](https://docs.mathjax.org/en/latest/input/tex/delimiters.html) This here is where I found how to change the delimiters. 
# Other neat things!
Recently I've been using [Obsidian](https://obsidian.md/) for note taking, and it also uses MathJax for it's (rendering?), and I figured maybe you all would be interesting in learning the (code?) for it to convert it into actual math symbols and such? 
Here's some of the pretty basic things you'll want. 
```js
(- "$" is to start and end a math statement

- ( _ )Underline is for the A sub B like A$_2$ = 3 and 4$_3$ = x

- \mathbb{} is when you wish to Bold something like the all intergers symbol $\mathbb{Z}$

- This is the end of a proof statement since I can't find any obsidian symbol for it ∎
- ^ can be used to make something an expnential
$4*4^2$

-'$$ $$' $$To-make-middle$$

- #Fractions   \frac and then the thing you wish to be a fraction
$$ \frac 4{2} $$

- <u>Underline</u>

Practice: 
Log$_5$ 5 = 1
lne$^2$ = 2

Some math symbols
∈ - element of a set
⇒ - then
∧ - and 
V - or
~ - not 
^- (Universal set)
∀ - For all
∃ - There exist
∎ - End proof
```
---
Or it will all look like this:

(- "$" is to start and end a math statement

- ( _ )Underline is for the A sub B like A$_2$ = 3 and 4$_3$ = x

- \mathbb{} is when you wish to Bold something like the all intergers symbol $\mathbb{Z}$

- This is the end of a proof statement since I can't find any obsidian symbol for it ∎
- ^ can be used to make something an expnential
$4*4^2$
- ∈ means something is an element of, same with ∎ cant find obsidian short cut so just copy pasted from google, such as 
A∈$\mathbb{Z}$

- <u>$$To-make-middle$$</u>

- #Fractions   \frac and then the thing you wish to be a fraction
$$ \frac 4{2} $$

- <u>Underline</u>

Practice: 
Log$_5$ 5 = 1
lne$^2$ = 2

More detailed formatting for Obsidian/MathJax: [Obsidian-Formatting](https://help.obsidian.md/How+to/Format+your+notes)<br/>

[back](../)
