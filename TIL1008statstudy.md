## Chapter 05 이산형 확률분포<br>-R과 Python을 활용한 기초통계플러스알파-

### 이산형 균등분포
- 서로 다른 n개의 이산점에서의 발생 확률이 1/n로 동일한 확률분포를 의미하며, $X\!\sim\!DU(1, n)$이라고 표현

**이산형 균등 확률변수의 pmf**

$P(X = x) = \frac{1}{n}, \quad x = 1, 2, \dots, n$

**이산형 균등분포의 평균과 분산**

$E(X) = \sum_{x=1}^{n} x \cdot \frac{1}{n} = \frac{1}{n} \sum_{x=1}^{n} x = \frac{1}{n} \cdot \frac{n(n+1)}{2} = \frac{n+1}{2}$

$E(X^2) = \sum_{x=1}^{n} x^2 \cdot \frac{1}{n} = \frac{1}{n} \sum_{x=1}^{n} x^2 = \frac{1}{n} \cdot \frac{n(n+1)(2n+1)}{6} = \frac{(n+1)(2n+1)}{6}$

$Var(X) = E(X^2) - [E(X)]^2 = \frac{(n-1)(n+1)}{12}$