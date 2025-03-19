# LIF
## LIF的微分方程表述为
$$  
\begin{cases}
\tau_m \frac{d}{dt}V(t)&=&E_t-V(t)+RI(t) &\text{if } V(t)\leq V_{th}\\
\\
V(t) &=& V_{reset} &\text{otherwise}
\end{cases}
$$  
如果没有这个 $\tau_m $,那么这个式子就会始终存在"$V=E-RI$",也就是说整个过程没有延迟与积分,膜电势会瞬时相应$I(t)$
当我们考虑膜电阻与电容时,会发现膜时间常数越大的体系,其存储信息的能力会更强,对于变化的敏感程度会更小,但是能整合更长时间段的电流刺激

## 随机输入的表现

