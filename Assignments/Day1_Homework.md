#Problem 1

Because $${\bf x}_i \sim \mathcal{N}({\bf x};\mu ,\Sigma)$$
According to the rules of normal distribution standardization
$$\frac{{\bf x} - \mu}{\sigma} \sim \mathcal{N}(0 ,{\bf I}_N)$$
$$ \mathcal{N}(\frac{{\bf x}_i - \mu}{U \Lambda^{\frac{1}{2}}};0 ,{\bf I}_N) = \mathcal{N}({\bf x};\mu ,\Sigma)$$
Since we already know
$${\bf h}_i \sim \mathcal{N}(0 ,{\bf I}_N)$$
we can conclude
$${\bf h}_i = \frac{{\bf x}_i - \mu}{U \Lambda^{\frac{1}{2}}}$$
$${\bf x}_i = \mu + U \Lambda^{\frac{1}{2}}{\bf h}_i$$