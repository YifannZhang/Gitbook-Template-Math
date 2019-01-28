# Section 1.1: examples

 
    S_{\frac{1}{T}}(f) \triangleq \underbrace{\sum_{k=-\infty}^{\infty} 
    S\left(f-\frac{k}{T}\right) \equiv
    \overbrace{\sum_{n=-\infty}^{\infty} s[n] \cdot e^{-i 2 \pi f n T}}^{\text{Fourier Series (DTFT)}}}_{\text { Possion Summation}}
    =\mathcal{F}\left\{\sum_{n=-\infty}^{\infty} s[n] \delta(t-n T)\right\}

$$
S_{\frac{1}{T}}(f) \triangleq \sum_{k=-\infty}^{\infty} S\left(f-\frac{k}{T}\right) \equiv
\sum_{n=-\infty}^{\infty} s[n] \cdot e^{-i 2 \pi f n T} 
$$

$$
 =\mathcal{F}\left\{\sum_{n=-\infty}^{\infty} s[n] \delta(t-n T)\right\}
$$