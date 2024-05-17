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
### 경우의 수가 많을 때
- 메모리를 활용해서 반복문을 줄여야함

#### 경우의 수의 합 중에 최고값 구하기
> - [프로그래머스 Lv. 2
/20240517_땅따먹기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240517_%EB%95%85%EB%94%B0%EB%A8%B9%EA%B8%B0.md)
- N x M 배열에서 N은 유지되고, M이 증가할 수록 지수만큼 증가된다면 높은 값만 사용하도록 함.
- 예를 들어 Map<key, value>에서 N은 key에 넣고, value에는 key에 들어갈 값 중에 높은 것 사용.

## 탐색 수가 많을 때
> - [프로그래머스 Lv. 2
/20240517_뒤에 있는 큰 수 찾기](https://github.com/ChoDragon9/algorithm-challenges/blob/main/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EC%8A%A4%20Lv.%202/20240517_%EB%92%A4%EC%97%90%20%EC%9E%88%EB%8A%94%20%ED%81%B0%20%EC%88%98%20%EC%B0%BE%EA%B8%B0.md)
- 스택을 활용해서 탐색 범위를 최소화 해야함
