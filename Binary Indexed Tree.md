# Binary Indexed Tree(Fenwick Tree)
- 전처리 결과의 질의와 변경을 효율적으로 하기 위해 사용됨
  - 일반적으로 질의를 O(1)로 하면 변경은 O(n)으로 됨
  - BIT로 구성하면 질의와 변경을 O(log n)으로 가능함
- 전처리 과정인 T를 O(n)으로 구성
- 질의(prefixSum)과 변경(update)를 O(log n)으로 구성

## Least Significant Bit
- 최하위 비트
- `k`를 이진수로 바꾼 뒤 첫 번째로 등장하는 1의 위치
- `-k`는 2의 보수로 비트 역전 후 +1하면 구할 수 있음
```
LSB(k):
  return k & -k
```

## 전처리
```
preprocessing(k):
  s = 0
  i = k + 1 - LSB(k)
  while k >= i
    s = s + A[k]
    k = k - 1
```

## 질의 및 변경
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
