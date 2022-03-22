---
layout: page
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
            <H1>Contrpositive and Congruence!</H1>
            <p>
            Some proofs we worked on in class! 
            </p>
            </center>
    </head>
</html>

# If $n^2$ is even, then n is even. 
Proposition: Suppose n∈$Z$
If $n^2$ is even, then n is even. <br/>
If we attempt a direct proof we'll see that it doesn't really get us anywhere:<br/>
Direct proof: Suppose that n∈$Z$ and $n^2$ is even. <br/>
By definition of even, there exists k∈$Z$ such that $n^2=2k$.<br/>
- Now we can't really do much from here. (Can't do nice things with $\sqrt{}$ and $Z$).<br/>
So from here we did a proof by contrapositive, meaning if the original statement is "If A, then B", the contrapositive will be "If not B, then not A"<br/>

# Proof by Contrapositive
If n is not even, then $n^2$ is not even.<br/>
<u>If n is odd, then $n^2$ is odd. </u> <br/>
Suppose n∈$Z$, and n is odd. <br/>
By definition of odd, there exists k∈$Z$ such that n=2k+1. If we square both sides we get $n^2=4k^2 + 4k +1$. The right side equals $2(2k^2+2k)+1$. Since $Z$ is closed under addition and mutliplication, $(2k^2+2k)∈Z$. Thus by definition, $n^2$ is odd. Therefore if $n^2$ is even, then n is even. ∎

# Congruence

Definition: Suppose a,b,n$∈Z$. We say that a is congruent to b mod n, denoted a≅b(modn), when n|(a-b)

Examples where n=3: <br/>
Is a ≅ b (mod3)?<br/>
- a = 3, b = 7<br/>
- a = 11, b = 4<br/>
- a = 12, b = 2<br/>
- a = -4, b = 2<br/>
- a = 31, b = 13<br/>
- a = 10, b = -10<br/>
<br/>
3 ≅ 7(mod3)? 3|(3-7) --> 3|(-4) No<br/>
11 ≅ 4(mod3)? 3|(11-4) --> 3|7 No<br/>
12 ≅ 2(mod3)? 3|(12-2) --> 3|10 No<br/>
-4 ≅  2(mod3)? 3|-6 yes<br/>
31 ≅ 13(mod3)? 3|18 yes<br/>
10 ≅ -10(mod3)? 3|20 no<br/>


# Proofs From class
Reminder- (Divides)Suppose that a,b∈$Z$. We say that b divides a, denoted b|a, when there exists an integer k such that a = bk. 
1. Proposition: Suppose a,b,c,n$∈Z$. If a≅b(modn) and b≅c(modn), then a≅c(modn).<br/>
a-b = nm, where n is an integer. <br/>
b-c = nk, where k is an integer. <br/>
b = nk+c<br/>
So a-(nk+c) = nm --> a-c = nm+nk --> n(m+k), since $Z$ is closed under addition and multiuplication, m+k$∈Z$. Therefore If a≅b(modn) and b≅c(modn), then a≅c(modn).∎<br/>
<br/>
2. Proposition: Suppose a,b,c,n$∈Z$. If a /≅ b(modn), then a+c /≅ b+c(modn)
Proof by contrapositive: if a+c≅ b+c(modn), then a≅b(modn). 
n|(a+c)-(b+c) equals n|a-b, which means a≅b(modn). Therefore if a /≅ b(modn), then a+c /≅ b+c(modn). ∎<br/>
3. Proposition: Suppose a,b,c,n$∈Z$. If a≅b(modn), then ac ≅bc(modn). <br/>
 a≅b(modn) = n|a-b. By definition of divides a-b = nf, where f$∈Z$. If you multipy both sides by c you get ac-bc = nfc. Let j =fc, Since $Z$ is closed under mutliplication j is an integer so ac-bc = nj. Which is n|ac-bc which is ac ≅bc(modn). Therefore If a≅b(modn), then ac ≅bc(modn).∎  <br/>

 [back](../BlogPage.md)

