<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
# Computational Complexity
- 알고리즘의 효율성을 표기해주는 표기법
- 알고리즘의 효율성 : 데이터 개수(n)가 주어졌을 때 기분 연산의 횟수
- 시간복잡도 : 알고리즘 연산수
- 공간복잡도 : 계산에 필요한 기억영역의 크기
- 빅오(Big-O), 빅오메가(Big-$\Omega$), 빅세타(Big-$\Theta$)

## Big-O
- 점근적 상한
- 최소의 증가율
$$
T(n) = O(f(n))  \Leftarrow T(n) \leq c \cdot f(n)
$$
(n > k한 모든 n에 대해)

빅오 크기 비교
O(1) < O(log n) < O(n) < O(nlogn) < O(n^2^) < O(n^3^) < O(2^n^) < O(n!)

## Big-$\Omega$
- 점근적 하한
- 최대의 증가율
$T(n) = \Omega(f(n))  \Leftarrow  T(n) \geq  c\cdot f(n)$

## Big-$\Theta$
- 상한과 하한이 같은지 아닌지
$T(n) = \Theta(f(n))  \Leftarrow c_1\cdot f(n) \leq T(n) \leq  c_2\cdot f(n)$
