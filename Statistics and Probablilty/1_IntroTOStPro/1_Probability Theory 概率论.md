# Probability Theory 概率论

- 概率是什么？

 当抛硬币时正反面的概率相同的意思是：当我们拋一个足够大的次数，也许是10000。 然后正面的次数应该接近$\frac{k}{2} = \frac{10000}{2} = 5000$.
 
 
- 模拟抛硬币的过程：

我们使用$x_i = 1, x_i = -1$代表正反面， 那么$S_{10000} = x_! + x_2 + \cdots + x_{10000}$ 会是多少？

在接下来的课程中我们会发现 **$|S_k| \geq 4 \sqrt{k}$ 小于 $2 * 10^{-8} = 0.000002\%$**.

- 结论：

$x_i = -1 $ 和 $x_i = 1 $ 的概率都为:$\frac{1}{2}$. 结论是$S_k$ 几乎或者说总是：$[-4\sqrt{k}, 4\sqrt{k}]$

$$if \; k \rightarrow \infty, \frac{4\sqrt{k}}{k} = \frac{4}{\sqrt{k}} \rightarrow 0$$

### What is probability theory?
> It is the math involved in proving(a precise version of) the statements blow.

**In most cases, we can approximate probabilities using simulations(Monte-Carlo simulations)**

> 然而计算概率是更好的选择：
>> 1.它提供了确切的答案。
>> 2. 比模拟快很多。 