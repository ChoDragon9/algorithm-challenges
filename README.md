# Algorithm Chellenges
재미있던 문제와 알고리즘/자료구조 기초 지식에 대해서 정리한다.

- [0. 학습](https://github.com/ChoDragon9/algorithm-challenges/tree/main/0.%20%ED%95%99%EC%8A%B5) : 알고리즘을 풀기 위한 선행 학습 내용을 정리한다.
- [프로그래머스 Lv. 2](https://github.com/ChoDragon9/algorithm-challenges/tree/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202) : 코딩테스트 난이도 Lv. 2를 정리한다.
- [프로그래머스](https://github.com/ChoDragon9/algorithm-challenges/tree/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4) : 코딩테스트 난이도 Lv. 0, 1를 정리한다.

## 최근 레벨 기록
![레벨 기록](https://github.com/ChoDragon9/algorithm-challenges/assets/17817719/0ce00625-50c5-4115-9001-9d46b34b01ee)


## 목표
- [x] 프로그래머스 3000위 이내 진입
- [ ] 프로그래머스 2000위 이내 진입
- [ ] 프로그래머스 1000위 이내 진입
- [ ] 프로그래머스 500위 이내 진입
- [ ] 프로그래머스 100위 이내 진입
- [ ] Hacker Rank 시작

## 회고
### 실수 줄이기
> - [24분 버림] [20240516_주식가격](https://school.programmers.co.kr/learn/courses/30/lessons/42584)
> - [15분 버림] [프로그래머스 Lv. 2
/20240515_k진수에서 소수 개수 구하기.md](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240515_k%EC%A7%84%EC%88%98%EC%97%90%EC%84%9C%20%EC%86%8C%EC%88%98%20%EA%B0%9C%EC%88%98%20%EA%B5%AC%ED%95%98%EA%B8%B0.md)
- 일정한 규칙이 있는 값은 시각화해서 규칙 파악하기 [프로그래머스 Lv. 2
/20240520_124 나라의 숫자](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240520_124%20%EB%82%98%EB%9D%BC%EC%9D%98%20%EC%88%AB%EC%9E%90.md)
- 최종 결과가 누적된 값인지, 아니면 누적 중에 멈춰야 되는 조건이 있는 지 정확히 확인 후 풀이하기
- 단순한 조건식도 정확히 확인하기
- 큰 수를 다룰 때는 BigInt를 사용한다. [프로그래머스 Lv. 2
/20240513_멀리 뛰기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240513_%EB%A9%80%EB%A6%AC%20%EB%9B%B0%EA%B8%B0.md)
- 자료구조를 활용하지 못하는 것은 수학으로 해결해보자 [프로그래머스 Lv. 2
/20240512_카펫](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240512_%EC%B9%B4%ED%8E%AB.md)
- 수학 공식을 모르겠어도 무작정 풀어보자 [프로그래머스 Lv. 2
/20240512_N개의 최소공배수](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240512_N%EA%B0%9C%EC%9D%98%20%EC%B5%9C%EC%86%8C%EA%B3%B5%EB%B0%B0%EC%88%98.md)
- 경우의 수는 보이는 데 최적을 모르겠을 때는 우선 모든 경우의 수를 구해보자 [프로그래머스
/20240506_N으로 표현](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4/20240506_N%EC%9C%BC%EB%A1%9C%20%ED%91%9C%ED%98%84.md)
- 문자열 정렬할 때 compareFn을 직접 만들 때가 있으므로 정확한 사용 방법을 알 필요가 있음 [프로그래머스
/20240509_문자열 내 마음대로 정렬하기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4/20240509_%EB%AC%B8%EC%9E%90%EC%97%B4%20%EB%82%B4%20%EB%A7%88%EC%9D%8C%EB%8C%80%EB%A1%9C%20%EC%A0%95%EB%A0%AC%ED%95%98%EA%B8%B0.md)

### 시간복잡도가 높을 때
- 배열/Set/Map을 변경하지 않고, 사칙 연산으로 계산하면 빠르게 됨 [프로그래머스 Lv. 2/20240522_시소 짝꿍](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240522_%EC%8B%9C%EC%86%8C%20%EC%A7%9D%EA%BF%8D.md)
- 제목 속에 답이 있음 창의적으로 생각하기!
- 큐를 구현할 때 shift는 성능이 좋지 않으므로 head 직접 관리하기!
- 증가 규칙이 피보나치 수열인지 파악. 나머지 값을 구하라고 하면 피보나치 수열 값 구할 때 구함. 마지막에 하면 늦음. 
- 메모리를 활용해서 반복문을 줄여야함
- 하향식일 때 경우의 수가 증가된다면 상향식으로 확인해보자 [프로그래머스
/20240507_정수 삼각형](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4/20240507_%EC%A0%95%EC%88%98%20%EC%82%BC%EA%B0%81%ED%98%95.md)
- 약수는 시작과 끝을 함께 구한다 [프로그래머스
/20240509_기사단원의 무기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4/20240509_%EA%B8%B0%EC%82%AC%EB%8B%A8%EC%9B%90%EC%9D%98%20%EB%AC%B4%EA%B8%B0.md)
- 큰 값의 범위를 탐색할 때는 수학으로 계산하고 인덱스 값을 이동해서 탐색 시간을 최적화함 [프로그래머스
/20240511_스킬체크_Lv3_1번](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4/20240511_%EC%8A%A4%ED%82%AC%EC%B2%B4%ED%81%AC_Lv3_1%EB%B2%88.md)

#### 소수를 빠르게 구하기 
> [프로그래머스
/20240510_소수 만들기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4/20240510_%EC%86%8C%EC%88%98%20%EB%A7%8C%EB%93%A4%EA%B8%B0.md)

- 2보다 큰 것 중에 2로 나눠지는 수는 소수가 아님
- 1과 n를 집합에 넣고, 루트 n수까지 1부터 2씩 증가하며 소수를 찾음
  - 집합의 갯수가 2개가 초과되면 소수가 아님

#### while 조건식 활용
- 최종적으로 최적화 할게 없다면 break, if 문을 최소화하자 [프로그래머스 Lv. 2
/20240511_짝지어 제거하기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240511_%EC%A7%9D%EC%A7%80%EC%96%B4%20%EC%A0%9C%EA%B1%B0%ED%95%98%EA%B8%B0.md)

#### 고유한 값을 넣을 때
> - [프로그래머스 Lv. 2
/20240516_롤케이크 자르기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240516_%EB%A1%A4%EC%BC%80%EC%9D%B4%ED%81%AC%20%EC%9E%90%EB%A5%B4%EA%B8%B0.md)
- Set을 활용하면 코드도 단순해지고, 탐색 시간이 빠름

#### 경우의 수의 합 중에 최고값 구하기
> - [프로그래머스 Lv. 2
/20240517_땅따먹기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240517_%EB%95%85%EB%94%B0%EB%A8%B9%EA%B8%B0.md)
- N x M 배열에서 N은 유지되고, M이 증가할 수록 지수만큼 증가된다면 높은 값만 사용하도록 함.
- 예를 들어 Map<key, value>에서 N은 key에 넣고, value에는 key에 들어갈 값 중에 높은 것 사용.

#### 탐색 수가 많을 때
> - [프로그래머스 Lv. 2
/20240517_뒤에 있는 큰 수 찾기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240517_%EB%92%A4%EC%97%90%20%EC%9E%88%EB%8A%94%20%ED%81%B0%20%EC%88%98%20%EC%B0%BE%EA%B8%B0.md)
- 스택을 활용해서 탐색 범위를 최소화 해야함

## 정리
> - [0.학습](https://github.com/ChoDragon9/algorithm-challenges/tree/main/0.%20%ED%95%99%EC%8A%B5) 내용 중 없는 것 정리

### 수학
- 등차수열의 합공식 : (첫 번째 수 + 마지막 수) * 길이 / 2
- 자카드 유사도
  - 집합 간의 유사도를 검사하는 방법
  - [프로그래머스 Lv. 2
/20240515_뉴스 클러스터링](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240515_%EB%89%B4%EC%8A%A4%20%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0%EB%A7%81.md)
- 소수는 1과 본인이 아닌 수로 나누어 떨어지지 않는 수. 본인을 다른 수로 나눠서 확인해야 함.
- 콜라츠 추측: 주어진 수가 1이 될 때까지 다음 작업을 반복하면, 모든 수를 1로 만들 수 있다는 추측
  1-1. 입력된 수가 짝수라면 2로 나눕니다. 
  1-2. 입력된 수가 홀수라면 3을 곱하고 1을 더합니다. 
  2. 결과로 나온 수에 같은 작업을 1이 될 때까지 반복합니다.
- 하샤드 수: x의 자릿수의합으로 x가 나눠질 때 

### 알고리즘
- 쿼드 트리 [프로그래머스
/20240508_쿼드압축 후 개수 세기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4/20240508_%EC%BF%BC%EB%93%9C%EC%95%95%EC%B6%95%20%ED%9B%84%20%EA%B0%9C%EC%88%98%20%EC%84%B8%EA%B8%B0.md)
- 최소 힙 [프로그래머스
/20240505_더 맵게](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4/20240505_%EB%8D%94%20%EB%A7%B5%EA%B2%8C.md)
- 캐시 교체 알고리즘 LRU(Least Recently Used) [프로그래머스 Lv. 2
/20240514_캐시](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240514_%EC%BA%90%EC%8B%9C.md)
  - 특정 한 캐시가 있음
  - 캐시 hit을 하면 가장 앞으로 이동
  - 캐시 miss를 하면 가장 앞으로 추가
  - 길이가 넘치면 뒤에서부터 삭제 
- 그래프, 너비 우선 탐색 [프로그래머스 Lv. 2
/20240515_깊이_너비우선탐색](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240515_%EA%B9%8A%EC%9D%B4_%EB%84%88%EB%B9%84%EC%9A%B0%EC%84%A0%ED%83%90%EC%83%89.md)
  1. 인접 리스트로 그래프를 만듬
  1. 그래프와 동일한 크기로 distance 누적 배열 만들기
  1. 큐 만들고, 시작 지점 enqueue
  1. dequeue 후 인접한 정점의 distance를 누적
  1. 해당 정점들을 enqueue 함
  1. 3번을 반복
  1. 도착 지점의 그래프 값을 확인
