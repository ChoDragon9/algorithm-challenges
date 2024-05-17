# Algorithm Chellenges
재미있던 문제와 알고리즘/자료구조 기초 지식에 대해서 정리한다.

- [0. 학습](https://github.com/ChoDragon9/algorithm-challenges/tree/main/0.%20%ED%95%99%EC%8A%B5) : 알고리즘을 풀기 위한 선행 학습 내용을 정리한다.
- [프로그래머스 Lv. 2](https://github.com/ChoDragon9/algorithm-challenges/tree/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202) : 코딩테스트 난이도 Lv. 2를 정리한다.
- [프로그래머스](https://github.com/ChoDragon9/algorithm-challenges/tree/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4) : 코딩테스트 난이도 Lv. 0, 1를 정리한다.

## 목표
- [ ] 프로그래머스 3000위 이내 진입
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
- 최종 결과가 누적된 값인지, 아니면 누적 중에 멈춰야 되는 조건이 있는 지 정확히 확인 후 풀이하기
- 단순한 조건식도 정확히 확인하기

### 경우의 수가 많을 때
- 메모리를 활용해서 반복문을 줄여야함

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
- 자카드 유사도
  - 집합 간의 유사도를 검사하는 방법
  - [프로그래머스 Lv. 2
/20240515_뉴스 클러스터링](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240515_%EB%89%B4%EC%8A%A4%20%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0%EB%A7%81.md)
- 소수는 1과 본인이 아닌 수로 나누어 떨어지지 않는 수. 본인을 다른 수로 나눠서 확인해야 함.

### 알고리즘
- 그래프, 너비 우선 탐색 [프로그래머스 Lv. 2
/20240515_깊이_너비우선탐색](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240515_%EA%B9%8A%EC%9D%B4_%EB%84%88%EB%B9%84%EC%9A%B0%EC%84%A0%ED%83%90%EC%83%89.md)
  1. 인접 리스트로 그래프를 만듬
  1. 그래프와 동일한 크기로 distance 누적 배열 만들기
  1. 큐 만들고, 시작 지점 enqueue
  1. dequeue 후 인접한 정점의 distance를 누적
  1. 해당 정점들을 enqueue 함
  1. 3번을 반복
  1. 도착 지점의 그래프 값을 확인
