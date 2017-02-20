수열 $a_{1}, a_{2}, \cdots, a_{n}$이 *연결되었다*는 것은 네 개의 위치 $i \lt j \lt k \lt l$가 $a_{i} = a_{k}, a_{j} = a_{l}, a_{i} \neq a_{j}$를 만족하는 경우가 존재한다는 것입니다.

수열 $a_{1}, a_{2}, \cdots, a_{n}$이 *$m$-연결되었다*는 것은 $1$ 이상 $n-m+1$ 이하의 $i$에 대해 $a_{i}, a_{i+1}, \cdots, a_{i+m-1}$이 연결되었다는 것입니다.

여러분에게 $m, n, r$이 주어졌습니다. 길이가 $n$이고 각 원소가 원소의 개수가 $r$인 집합에 속하는 $m$-연결된 수열의 개수를 $10^{9}+7$로 나눈 나머지를 구하세요.

### 입력 형식

첫 번째 줄에 세 개의 정수 $m, n, r$가 주어집니다. ($4 \le m \le 8, m \le n \le 50, 2 \le r \le 50$)

### 출력 형식

조건을 만족하는 $m$-연결된 수열의 개수를 $10^{9}+7$로 나눈 나머지를 출력합니다.

### 예제

<table class='table table-bordered table-condensed'>
 <thead>
  <tr>
   <th style="width: 50%;">입력</th>
   <th style="width: 50%;">출력</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td class="code-font">4 5 3</td>
   <td class="code-font">6</td>
  </tr>
 </tbody>
</table>

### 참고

길이가 $5$인 4-연결된 수열들은 다음과 같습니다.

* $(1,2,1,2,1)$
* $(1,3,1,3,1)$
* $(2,1,2,1,2)$
* $(2,3,2,3,2)$
* $(3,1,3,1,3)$
* $(3,2,3,2,3)$