# LIF
## LIF的微分方程表述为

$$
\begin{aligned}
&\tau_m \frac{dV(t)}{dt} = E_t - V(t) + R I(t) \quad \text{if } V(t) \leq V_{th} \\
&\text{当 } V(t) \text{ 超过阈值时，重置为 } V(t) = V_{\text{reset}}
\end{aligned}
$$

如果没有 $\tau_m$，方程会退化为 $V = E_t - R I(t)$，这意味着膜电位会瞬间响应输入电流 $I(t)$，失去积分和延迟特性。

当考虑膜电阻和电容时，时间常数 $\tau_m$ 越大：
- 系统能存储更长时间的信息，
- 对突变的敏感度降低，
- 但能整合更长时间的电流刺激。

## 随机输入的表现