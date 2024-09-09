# Kombinatorika
## Permutace
$$
P(n)=n!
$$
$$
P(n)=V_{n}(n)
$$
## Variace
Záleží na pořadí
### Variace bez opakování
$$
V_{k}(n)=\frac{n!}{(n-k)!}
$$
### Variace s opakováním
$$
V'_{k}(n)=n^{k}
$$
## Kombinace
Nezáleží na pořadí
### Kombinace bez opakování
$$
C_{k}(n)=\binom{n}{k}=\frac{n!}{k!*(n-k)!}=\frac{V_{k}(n)}{k!}
$$
### Kombinace s opakováním
$$
C'_{k}(n)=\binom{n+k-1}{k}
$$
# Posloupnosti
$2,4,6,8,10,\dots,2n\dots$ -> $\infty$
$2,4,8,16,32,\dots,2^{n}\dots$ -> $\infty$
$0,0,0,0,\dots$ -> $0$
$-1,1,-1,1,\dots$ -> nemá limitu
$\frac{n-1}{n}$->$0,\frac{1}{2},\frac{2}{3},\frac{3}{4},\dots$ -> $1$
$(-1)^{n}\frac{1}{n}$->$-1,\frac{1}{2},-\frac{1}{3},\frac{1}{4},\dots$ -> $0$
$-1+\frac{1}{2}-\frac{1}{3}+\frac{1}{4}$ -> řada - sečteme všechny členy posloupnosti
![[457815833_1042722987441451_7709570424640182165_n.jpg]]