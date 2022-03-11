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
```<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script> <br/>`
```<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>`
This will allow you to use LaTex formatting in your html/markdown files. Now if you wish to change the delimiters that it will use, like to the ones Obsidian uses ($ $), than you can place this: 
    <code>
        <script>
            window.MathJax = {
            tex: {
            inlineMath: [['$', '$'], ['\\(', '\\)']]
            }
            };
        </script>
    </code>
