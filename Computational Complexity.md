---


---

<h1 id="computational-complexity">Computational Complexity</h1>
<ul>
<li>알고리즘의 효율성을 표기해주는 표기법</li>
<li>알고리즘의 효율성 : 데이터 개수(n)가 주어졌을 때 기분 연산의 횟수</li>
<li>시간복잡도 : 알고리즘 연산수</li>
<li>공간복잡도 : 계산에 필요한 기억영역의 크기</li>
<li>빅오(Big-O), 빅오메가(Big-Ω), 빅세타(Big-Θ)</li>
</ul>
<h2 id="big-o">Big-O</h2>
<ul>
<li>점근적 상한</li>
<li>최소의 증가율<br>
T(n) = O(f(n)) ←  T(n) ≤ c⋅f(n)<br>
(n &gt; k한 모든 n에 대해)</li>
</ul>
<p>빅오 크기 비교<br>
O(1) &lt; O(log n) &lt; O(n) &lt; O(nlogn) &lt; O(n<sup>2</sup>) &lt; O(n<sup>3</sup>) &lt; O(2<sup>n</sup>) &lt; O(n!)</p>
<h2 id="big-ω">Big-Ω</h2>
<ul>
<li>점근적 하한</li>
<li>최대의 증가율<br>
T(n) = Ω(f(n))  ←  T(n) ≥  c⋅f(n)</li>
</ul>
<h2 id="big-θ">Big-Θ</h2>
<ul>
<li>상한과 하한이 같은지 아닌지<br>
T(n) = Θ(f(n))  ← c<sub>1</sub>⋅ f(n) ≤ T(n) ≤  c<sub>2</sub>⋅ f(n)</li>
</ul>

