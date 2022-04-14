<center>
<h1>
More Proofs!
</h1>
</center>
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
</head>

# Start
So These are a couple proofs we did for a homework the other day. A couple of them were rough and I just oculdn't grasp what to do for a while, so I'm still not sure if I got them or not haha but I guess we'll see when I get the grades back.

# Without my answers
1. Prove that if x is an odd integer, then $x^3$ is odd.


2. Suppose a∈$Z$. </br> Prove that if $a^2|a$, then a ∈ {-1,0,1}. (Hint. You might find it helpful to use cases.)


3. Let x and y be real numbers, and suppose that x is rational. </br>
Prove that if xy is irrational, then y is irrational. 


4. Suppose that $a,b,c∈Z$. </br>
Prove that if a does not divide bc, then a does not divide b and a does not divide c.


5. Prove that every odd integer is the difference of 2 perfect squares. </br>
(Hint. Start by playing around with other examples. Do you notice any patterns in which squares you can use for a particular odd number? If you can find a simple pattern, then you can build your proof strategy from it.)
(Ex. she gave us was $7=4^2 - 3^2$)

# My answers
A solid 3 of these I'm quite confident on but 2 and 5 I think I'm missing a couple steps maybe?

1. Prove that if x is an odd integer, then $x^3$ is odd. </br>
Suppose $x∈Z$ that is odd, then there exists $k∈Z$ such that $x= 2k+1$. If we cube each side then we get $x^3=8k^3 + 12k^2 + 6k +1$. The right side of this equation equals $2(4k^3 + 6k^2 +3k) + 1$. Let b = $4k^3 + 6k^2 +3k$. Since $Z$ is closed under addition and multiplication, $b∈Z$. So $x^3=2b+1$ Thus by definition $n^3$ is odd. ∎


2. Suppose $a∈Z$. Prove that if $a^2|a$, then a ∈ {-1,0,1}. (Hint. You might find it helpful to use cases.)
By definition of divides $a^2|a$ is equivalent to $a=a^2v$, where v is an integer. {-1,1} are the only integers that square to 1, and 0 squares to 0, meaning that these are the only integers when squared that can be a factor of themself. Thus if $a^2|a$, then a ∈ {-1,0,1}. ∎


3. Let x and y be real numbers, and suppose that x is rational. Prove that if xy is irrational, then y is irrational. 
Proof by contrapositive: Let x and y be real numbers, and suppose that x is rational. If y is rational, then xy is rational. By definition of rational, x can be expressed as m/n, $m,n∈Z$ and n≠0, and y can be expressed as a/b, where $a,b∈Z$ and b≠0. So xy = (m/n)(a/b) = ma/nb. Since n and b are both ≠0, nb≠0 and $R$ falls under multiplication, ma/nb is a rational number. ∎


4. Suppose that $a,b,c∈Z$. Prove that if a does not divide bc, then a does not divide b and a does not divide c. 
Proof by contrapositive: Suppose $a,b,c∈Z$.We are trying to show that  if a|b V a|c, then a|bc. 
- Case 1: Suppose a|b. By definition of divides, a|b is equivalent to b = ak, where $k∈Z$. If you multiply both sides by c you get bc=akc. Let kc=m, since $Z$ is closed under multiplication, $m∈Z$. So bc=am, therefore a|bc
- Case 2: Suppose a|c. By definition of divides, a|c is equivalent to c = ag, where $g∈Z$. If you multiply both sides by b you get bc=agb. Let gb=x, since $Z$ is closed under multiplication, $g∈Z$. So bc=ax.
Therefore a|bc. ∎


5. Prove that every odd integer is the difference of 2 perfect squares. 
(Hint. Start by playing around with other examples. Do you notice any patterns in which squares you can use for a particular odd number? If you can find a simple pattern, then you can build your proof strategy from it.)
- Suppose x is an odd integer. We want to show that $x=(.5a+.5)^2 - (.5a-.5)^2$, where $a∈Z$. First we start with a, which we can express as $.25a^2+.5a+.25 - (.25a^2-.5a+.25)$. We can now unfoil it to get $(.5a+.5)^2-(.5a-.5)^2$ and since $Z$ is closed under multiplication, addition and subtraction, $(.5a+.5)^2,(.5a-.5)^2∈Z$. Therefore every odd integer is the difference of 2 perfect squares. ∎


$(.5x+.5)(.5x+.5)=.25x^2+.25x+.25x+.25$ -
$(.5x-.5)(.5x-.5)=.25x^2-.25x-.25x+.25$
= x