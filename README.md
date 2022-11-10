# **2023 Turkish Election Forecast (Türkiye 2023 Seçimleri Tahmini)**

> We simulate 50000 draws from a Dirichlet distribution for each poll.
>
> The probability distribution function of a Dirichlet distribution is:
>
> $\{x_1, \dots, x_K\} \sim\frac{1}{B(\boldsymbol{\alpha})}\prod_{i=1}^Kx_i^{\alpha_i - 1}$ with $K\le 2$, $x_i \in (0,1)$, and $\sum_{i=1}^Kx_i = 1$.
>
> Our $x_i$ are the poll percentages for each party $i$.
>
> The probability of victory for each party is the number of draws out of the total in which the simulated election is won by the respective party.

 ---------------------------------
 
### **Updated: 10.11.2022**
 
![Graph, X](/fig.png)

