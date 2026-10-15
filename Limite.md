#def
>[!abstract] Definizione
>Sia $f:A \subseteq \mathbb{R}^d \to \mathbb{R}$
>Sia $x_{0}$ un [[Punto di Accumulazione]] di $A$
>Sia $l \in \mathbb{R}$
>Si dice che
>$$\lim_{ x \in A \to x_{0} }f(x)=l$$
>Se:
>$$
>\forall \epsilon>0 ~ \exists \delta>0~ t.c.~ d(x; x_{0})<\delta~ \text{(ovvero: } x \in B_{\delta}(x_{0}) \text{)}~ \implies |f(x)-l|<\epsilon
>$$


#prop
> [!quote] Proposizione
> Sia: 
> $$
\lim_{ (x, y) \to (x_{0}, y_{0}) } f(x, y) = l$$
Sia:$$
\begin{cases}
x(t) = x_{0} + \alpha t \\
y(y) = y_{0} + \beta t \\
\end{cases}$$
allora: $$
\lim_{ t \to 0 } f(x_{0}+\alpha t, y_{0}+\beta t) = l 
$$

#dim
Per ipotesi:
$$
\lim_{ x,y \to (x_{0}, y_{0}) } f(x, y)=l 
$$
implica che:
$\forall \epsilon>0, \exists \delta>0$ tale che :
se 
	la distanza di un punto qualsiasi $P=(x, y)$ nel dominio, dal punto $(x_{0}, y_{0})$ è inferiore a $\delta$:
$$
0<\sqrt{ (x-x_{0})^2 +(y-y_{0})^2}<\delta
$$
allora:
	la distanza dell'immagine di $P$ dal valore del limite $l$, è inferiore all'$\epsilon$:
	$$
0<|f(x, y)-l|<\epsilon
$$

Ora consideriamo una generica retta passante per il punto $(x_{0}, y_{0})$, parametrizzata a $t$.
I punti di questa 



