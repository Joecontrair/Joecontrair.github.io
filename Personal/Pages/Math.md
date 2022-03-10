---
layout: default
usemathjax: true
---

Notes From class: 

a,b ∈ $Z$
The Division Algorithm (Actually a theorem):
Suppose a∈$Z$ and b ∈ $Z^+$. Then there exists <u>unique</u> integers q and r such that $a = bq+r$ and $0<=r<b$
(Follows from the 'Well Ordering principle')

<u>unique:</u> x is unique if there is only one such value. x and y are <u>distinct</u> if x/=y. 
__________________________________________
Definition: Suppose a∈$Z$. We say that a is even when there exists n∈$Z$ such that a=2n. We say that a is odd when there exists k∈$Z$ such that a=2k+1

Claim: Suppose a∈$Z$. Then a is even or a is odd, and a can't be both even and odd. 

Could a be both even and odd? Suppose so. This means that there exists integers k and n such that a=2n = 2k+1. Then n=k+(1/2), and so n-k=(1/2). 
But since n and k are integers and $Z$ is closed under subtraction, n-k∈$Z$. This would make (1/2) an integer, which it isn't. 

Recall: 
Definition: Suppose a and b are integers. Then b divideds a, denoted b|a, when there exists an integer k such that a = bk.

Observation: b|a <=> the (unique) remainder when we divide a by b is 0.
Suppose b|a. this means a=bk for some k∈$Z$. In other words, a=bk+0 where b,0∈$Z$ and 0<=0<b. Thus the remainder when we divide a by b, the remainder is 0. 
<== : Suppose that when we divide b by a using the division algorithm, the remainder is 0. In other words, there exists q∈$Z$ such that a=bq+0=bq. Thus, by definition of divisor, b|a. Therefore, b|a if and only if the remainder on dividing a by b is 0. ∎
_________________________
Proposition: If n∈$Z$, then the remainder we get when we divide $n^2$ by 4 is either 0 or 1. 

Case 1: Suppose a is an even integer. Then a=2n, and $a^2$ = $4n^2$. If we then divide $4n^2$ by 4 we get $n^2$.  Let q = $n^2$, since $z$ is closed under multiplication and n∈$Z$, q∈$Z$. Thus giving us 4q+0, which leaves us with a remainder of 0. ∎

Case 2: Suppose b is an odd integer. Then $b=2k+1$, and $b^2 = 4k^2+4k+1$. We then can foil $4k^2+4k$ into $4(k^2 + k) + 1$. Let q = $k^2 + k$, since $Z$ is closed under addition and multiplication, and k∈$Z$, q∈$Z$. Thus we get 4q+1, leaving a remainder of 1. ∎
___
Other Proposition: If n∈$Z$, then the remainder when you divide $n^2$ by 3 is 0 or 1.

Case 1: Suppose c is an integer that is a multiple of 3, then $c=3d$. With this we can square c, giving $c^2 = 9d^2$. We can then reformat to $3(3d^2)$. Let $m=3d^2$, since $Z$ is closed under multiplication, $3d^2∈Z$, $m∈Z$. This gives us 3m+0, thus leaving a remainder of 0. ∎

Case 2: Suppose g is an even integer that isn't a multiple of 3, then $g=2f$. We then square g, getting $4n^2$. Let $p=f^2$, since $Z$ is closed under multiplication and $g∈Z$, $f∈Z$. Thus when 3 goes into $4f^2$ we get a remainder of 1. ∎

Case 3: Suppose ∎ is an odd integer that isn't a multiple of 3, then $∎=2s+1$. We then square it getting $∎^2 = 4s^2 + 4s + 1$. 
QED

___
Professors proof for 1:
Suppose n∈$Z$. Then we know n is even or n is odd.

Case 1: n is even, then $n=2k$ for some k∈$Z$. Then $n^2 = 4k^2 = 4k^2 + 0$. Let q = $k^2$ and r=0, then q∈$Z$, since $Z$ is closed under multiplication and r∈$Z$, and $n^2=4q+r$ and $0<=r<4$. So the remainder when you divide $n^2$ by 4 is 0. ∎

Case 2: n is odd, then $n=2k+1$ for some k∈$Z$. Then $n^2 = 4k^2 + 4k + 1 = 4(k^2 + k) + 1$. Let q = $k^2 + k$, then q∈$Z$ and $n^2=4q+1$, where 0<=1<4. Thus the remainder when you divide $n^2$ by 4 is 1. ∎

Professors proof for 2:
Suppose n is an integer. 
By the division algorithm, there exists Integer k such that $n=3k+r$ where r= 0, 1 or 2.

Case 1(r=0): n is divisible by 3. $n=3k$ where k∈$Z$. $n^2=(3k)^2=9k^2=3(3k^2)+0$. So if we let $q=3k^2$ and r=0, then q∈$Z$($Z$ is closed under...) and r∈$Z$ and $n^2=3q+r$ and $0<=r<3$. So the remainder when you divide $n^2$ by 3 is 0. ∎

Case 2(r=1): Then $n=3k+1$. So=, $n^2=(3k+1)^2=9k^2+6k+1=3(3k^2+2k)+1$. Let q = $3k^2+2k$, since $Z$ is closed under multiplication and n,k are integers, q is an integer, and r∈$Z$ and $n^2=3q+r$ and $0<=r<3. So the remainder for $n^2$ is 1.∎

Case 3:(r=2) then $n=3k+2$. $n^2=(3k+2)^2=9k^2+12k+4=3(3k^2+4k)+4=3(3k^2+4k+1)+1$. Let $q=3k^2+4k+1$,($Z$ is closed under...) and r∈$Z$ and $n^2=3q+r$ and $0<=r<3$. So the remainder for $n^2$ is 1. ∎

