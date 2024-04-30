# Binary Indexed Tree(Fenwick Tree)
- 전처리 결과의 질의와 변경을 효율적으로 하기 위해 사용됨
  - 일반적으로 질의를 O(1)로 하면 변경은 O(n)으로 됨
  - BIT로 구성하면 질의와 변경을 O(log n)으로 가능함
- 전처리 과정인 T를 O(n)으로 구성
- 질의(prefixSum)과 변경(update)를 O(log n)으로 구성

## 의사 코드
- `A` 원본 데이터
- `T` 전처리 데이터
- `k` 1부터 시작하는 인덱스
### Least Significant Bit
- 최하위 비트
- `k`를 이진수로 바꾼 뒤 첫 번째로 등장하는 1의 위치
- `-k`는 2의 보수로 비트 역전 후 +1하면 구할 수 있음

```
10진수 6의 LSB를 구하는 과정

  0110 = 6의 2진수 표현
& 1010 = 6의 2진수를 2의 보수로 표현
------
  0010 = 2의 2진수
```

```
LSB(k):
  return k & -k
```

### 전처리
```
preprocessing(k):
  s = 0
  i = k + 1 - LSB(k)
  while k >= i:
    s = s + A[k]
    k = k - 1
  return s
```

### 질의 및 변경
```
prefix_sum(k):
  s = 0
  while k >= 1:
    s = s + T[k]
    k = k - LSB(k)
  return s

update(k, x):
  d = x - A[k]
  while k <= n:
    T[k] = T[k] + d
    k = k + LSB(k)
```

## 자바스크립트 코드
```js
function preprocess(arr) {
  return arr.map((_, i) => preprocessInner(i, arr));
}

function preprocessInner(i, arr) {
  let endIndex = i + 1 - lsb(i);
  let total = 0;

  for (; i >= endIndex; i--) {
    total += arr[i]
  }

  return total;
}

function lsb(i) {
  const k = i + 1;
  return k & -k
}

function prefixSum(processedArr, i) {
  let total = 0;

  while (i >= 0) {
    total += processedArr[i]
    i -= lsb(i)
  }

  return total;
}

function update (arr, processedArr, i, x) {
  const diff = x - arr[i];
  while (i < processedArr.length) {
    processedArr[i] += diff;
    i += lsb(i)
  }
}

const arr = [1, 2, 0, 4, 1, 3, 5, 9, 8, 6]
const processedArr = preprocess(arr);

console.log(processedArr.join(',') === '1,3,0,7,1,4,5,25,8,14');
console.log(prefixSum(processedArr, 0) === 1);
console.log(prefixSum(processedArr, 1) === 3);
console.log(prefixSum(processedArr, 3) === 7);

update(arr, processedArr, 4, 3);
console.log(processedArr.join(',') === '1,3,0,7,3,6,5,27,8,14');
```
