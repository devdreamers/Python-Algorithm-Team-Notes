### Part 1 코딩 테스트, 무엇을 어떻게 준비할까?

#### 1장 코딩 테스트 개요

* 코딩 테스트 개념과 배경
* 실습 환경 구축하기
* 복잡도
    * [파이썬 수행 시간 측정 방법](/1/1.py)
    * [선택 정렬과 기본 정렬 라이브러리의 수행 시간 비교](/1/2.py)

### Part 2 주요 알고리즘 이론과 실전 문제

* 중복 제외: set, s1.difference(s2), s1 - s2, [ i for i in list if i not in list2 ]


#### 3장 그리디
* 키워드: 가장 큰, 가장 작은 , 최적의 해
* 이론
    * 당장 좋은 것만 선택하는 그리디
    * 거스름돈 문제: ([Python 3.7 코드](/3/1.py))
* 실전
    * 동빈이의 큰 수의 법칙: ([Python 3.7 코드](/3/2.py))
    * 숫자 카드게임: ([Python 3.7 코드](/3/4.py))
    * 1이 될 때까지: ([Python 3.7 코드](/3/6.py))

#### 4장 구현

* 이론
    * 아이디어를 코드로 바꾸는 구현
    * 상하좌우: ([Python 3.7 코드](/4/1.py))
    * 시각: ([Python 3.7 코드](/4/2.py))
* 실전
    * 왕실의 나이트: ([Python 3.7 코드](/4/3.py))
    * 게임 개발: ([Python 3.7 코드](/4/4.py))

#### 5장 DFS/BFS

* 이론
    * 꼭 필요한 자료구조 기초
    * 탐색 알고리즘 DFS/BFS
    * 스택 구현 예제: ([Python 3.7 코드](/5/1.py))
    * 큐 구현 예제: ([Python 3.7 코드](/5/2.py))
    * 무한히 반복되는 재귀함수 예제: ([Python 3.7 코드](/5/3.py))
    * 재귀함수의 종료 조건 예제: ([Python 3.7 코드](/5/4.py))
    * 2가지 방식으로 구현한 팩토리얼 예제: ([Python 3.7 코드](/5/5.py))
    * 인접 행렬 예제: ([Python 3.7 코드](/5/6.py))
    * 인접 리스트 예제: ([Python 3.7 코드](/5/7.py))
    * DFS: ([Python 3.7 코드](/5/8.py))
    * BFS: ([Python 3.7 코드](/5/9.py))
* 실전
    * 음료수 얼려 먹기: ([Python 3.7 코드](/5/10.py))
    * 미로 탈출: ([Python 3.7 코드](/5/11.py))

#### 6장 정렬

* 이론
    * 기준에 따라서 데이터를 정렬
    * 선택 정렬: ([Python 3.7 코드](/6/1.py))
    * 스와프(Swap): ([Python 3.7 코드](/6/2.py))
    * 삽입 정렬: ([Python 3.7 코드](/6/3.py))
    * 퀵 정렬: ([Python 3.7 코드](/6/4.py))
    * 파이썬의 장점을 살린 퀵 정렬: [Python 3.7 코드](/6/5.py)
    * 계수 정렬: ([Python 3.7 코드](/6/6.py))
    * 정렬 라이브러리 기본 예제: ([Python 3.7 코드](/6/7.py))
    * 정렬 라이브러리 키(Key) 기준 정렬 예제: ([Python 3.7 코드](/6/9.py))
* 실전
    * 위에서 아래로: ([Python 3.7 코드](/6/10.py))
    * 성적이 낮은 순서대로 학생 출력하기: ([Python 3.7 코드](/6/11.py))
    * 두 배열의 원소 교체: ([Python 3.7 코드](/6/12.py))

#### 7장 이진 탐색

* 이론
    * 범위를 반씩 좁혀가는 탐색
    * 순차 탐색: ([Python 3.7 코드](/7/1.py))
    * 재귀 함수를 이용한 이진 탐색: ([Python 3.7 코드](/7/2.py))
    * 반복문을 이용한 이진 탐색: ([Python 3.7 코드](/7/3.py))
    * 파이썬에서 빠르게 입력 받기: [Python 3.7 코드](/7/4.py)
* 실전
    * 부품 찾기
        * 이진 탐색으로 해결: ([Python 3.7 코드](/7/5.py))
        * 계수 정렬로 해결: ([Python 3.7 코드](/7/6.py))
        * 집합(Set) 자료형으로 해결: ([Python 3.7 코드](/7/7.py))
    * 떡볶이 떡 만들기: ([Python 3.7 코드](/7/8.py))

#### 8장 다이나믹 프로그래밍

* 이론
    * 비효율적인 피보나치 수열 구현: ([Python 3.7 코드](/8/1.py))
    * 피보나치 수열 (Top-bottom): ([Python 3.7 코드](/8/2.py))
    * 피보나치 수열 (Bottom-top): ([Python 3.7 코드](/8/4.py))
* 실전
    * 1로 만들기: ([Python 3.7 코드](/8/5.py))
    * 개미 전사: ([Python 3.7 코드](/8/6.py))
    * 바닥 공사: ([Python 3.7 코드](/8/7.py))
    * 효율적인 화폐 구성: ([Python 3.7 코드](/8/8.py))

#### 9장 최단 경로

* 이론
    * 가장 빠른 길 찾기
    * 간단한 다익스트라 알고리즘: ([Python 3.7 코드](/9/1.py))
    * 개선된 다익스트라 알고리즘 (우선순위 큐): ([Python 3.7 코드](/9/2.py))
    * 플로이드 워셜 알고리즘: ([Python 3.7 코드](/9/3.py))
* 실전
    * 미래 도시: ([Python 3.7 코드](/9/4.py))
    * 전보: ([Python 3.7 코드](/9/5.py))

#### 10장 기타 그래프 이론

* 이론
    * 다양한 그래프 알고리즘
    * 간단한 서로소 집합 알고리즘: ([Python 3.7 코드](/10/1.py))
    * 개선된 서로소 집합 알고리즘 (경로 압축): ([Python 3.7 코드](/10/3.py))
    * 서로소 집합을 활용한 사이클 판별: ([Python 3.7 코드](/10/4.py))
    * 크루스칼 알고리즘: ([Python 3.7 코드](/10/5.py))
    * 위상 정렬: ([Python 3.7 코드](/10/6.py))
* 실전
    * 팀 결성: ([Python 3.7 코드](/10/7.py))
    * 도시 분할 계획: ([Python 3.7 코드](/10/8.py))
    * 커리큘럼: ([Python 3.7 코드](/10/9.py))

### Part 3 알고리즘 유형별 기출문제

#### 11장 그리디

* 모험가 길드 (핵심 유형): ([Python 3.7 코드](/11/1.py))
* 곱하기 혹은 더하기 (Facebook 인터뷰 기출): ([Python 3.7 코드](/11/2.py))
* [문자열 뒤집기](https://www.acmicpc.net/problem/1439) (핵심 유형): ([Python 3.7 코드](/11/3.py))
* 만들 수 없는 금액 (K 대회 기출): ([Python 3.7 코드](/11/4.py))
* 볼링공 고르기 (S 기관 입학 테스트): ([Python 3.7 코드](/11/5.py))
* [무지의 먹방 라이브](https://programmers.co.kr/learn/courses/30/lessons/42891) (카카오): ([Python 3.7 코드](/11/6.py))

#### 12장 구현

* [럭키 스트레이트](https://www.acmicpc.net/problem/18406) (핵심 유형): ([Python 3.7 코드](/12/1.py))
* 문자열 재정렬 (Facebook 인터뷰 기출): ([Python 3.7 코드](/12/2.py))
* [문자열 압축](https://programmers.co.kr/learn/courses/30/lessons/60057) (카카오): ([Python 3.7 코드](/12/3.py))
* [자물쇠와 열쇠](https://programmers.co.kr/learn/courses/30/lessons/60059) (카카오): ([Python 3.7 코드](/12/4.py) )
* [뱀](https://www.acmicpc.net/problem/3190) (삼성): ([Python 3.7 코드](/12/5.py))
* [기둥과 보 설치](https://programmers.co.kr/learn/courses/30/lessons/60061) (카카오): ([Python 3.7 코드](/12/6.py))
* [치킨 배달](https://www.acmicpc.net/problem/15686) (삼성): ([Python 3.7 코드](/12/7.py))
* [외벽 점검](https://programmers.co.kr/learn/courses/30/lessons/60062) (카카오): ([Python 3.7 코드](/12/8.py))

#### 13장 DFS/BFS

* [특정 거리의 도시 찾기](https://www.acmicpc.net/problem/18352) (핵심 유형): ([Python 3.7 코드](/13/1.py))
* [연구소](https://www.acmicpc.net/problem/14502) (삼성): ([Python 3.7 코드](/13/2.py))
* [경쟁적 전염](https://www.acmicpc.net/problem/18405) (핵심 유형): ([Python 3.7 코드](/13/3.py))
* [괄호 변환](https://programmers.co.kr/learn/courses/30/lessons/60058) (카카오): ([Python 3.7 코드](/13/4.py) )
* [연산자 끼워 넣기](https://www.acmicpc.net/problem/14888) (삼성): ([Python 3.7 코드](/13/5.py))
* [감시 피하기](https://www.acmicpc.net/problem/18428) (핵심 유형): ([Python 3.7 코드](/13/6.py))
* [인구 이동](https://www.acmicpc.net/problem/16234) (삼성): ([Python 3.7 코드](/13/7.py))
* [블록 이동하기](https://programmers.co.kr/learn/courses/30/lessons/60063) (카카오): ([Python 3.7 코드](/13/8.py))

#### 14장 정렬

* [국영수](https://www.acmicpc.net/problem/10825) (핵심 유형): ([Python 3.7 코드](/14/1.py))
* [안테나](https://www.acmicpc.net/problem/18310) (국내 S 교육 기관 선발 평가): ([Python 3.7 코드](/14/2.py))
* [실패율](https://programmers.co.kr/learn/courses/30/lessons/42889) (카카오): ([Python 3.7 코드](/14/3.py))
* [카드 정렬하기](https://www.acmicpc.net/problem/1715) (핵심 유형): ([Python 3.7 코드](/14/4.py))

#### 15장 이진 탐색

* 정렬된 배열에서 특정 수의 개수 구하기 (Zoho 인터뷰 기출): ([Python 3.7 코드](/15/1.py))
* 고정점 찾기 (Amazon 인터뷰 기출): ([Python 3.7 코드](/15/2.py))
* [공유기 설치](https://www.acmicpc.net/problem/2110) (핵심 유형): ([Python 3.7 코드](/15/3.py))
* [가사 검색](https://programmers.co.kr/learn/courses/30/lessons/60060) (카카오): ([Python 3.7 코드](/15/4.py))

#### 16장 다이나믹 프로그래밍

* 금광 (Flipkart 인터뷰 기출): ([Python 3.7 코드](/16/1.py))
* [정수 삼각형](https://www.acmicpc.net/problem/1932) (IOI): ([Python 3.7 코드](/16/2.py))
* [퇴사](https://www.acmicpc.net/problem/14501) (삼성): ([Python 3.7 코드](/16/3.py))
* [병사 배치하기](https://www.acmicpc.net/problem/18353) (핵심 유형): ([Python 3.7 코드](/16/4.py))
* 못생긴 수 (Google 인터뷰 기출): ([Python 3.7 코드](/16/5.py))
* 편집 거리 (Goldman Sachs 인터뷰 기출): ([Python 3.7 코드](/16/6.py))

#### 17장 최단 경로

* [플로이드](https://www.acmicpc.net/problem/11404) (핵심 유형): ([Python 3.7 코드](/17/1.py))
* 정확한 순위 (K 대회 기출): ([Python 3.7 코드](/17/2.py))
* 화성 탐사 (ICPC): ([Python 3.7 코드](/17/3.py))
* 숨바꼭질 (USACO): ([Python 3.7 코드](/17/4.py))

#### 18장 기타 그래프 이론

* 여행 계획 (핵심 유형): ([Python 3.7 코드](/18/1.py))
* 탑승구 (CCC): ([Python 3.7 코드](/18/2.py))
* 어두운 길 (University of Ulm Local Contest): ([Python 3.7 코드](/18/3.py))
* [행성 터널](https://www.acmicpc.net/problem/2887) (COCI): ([Python 3.7 코드](/18/4.py))
* [최종 순위](https://www.acmicpc.net/problem/3665) (ICPC): ([Python 3.7 코드](/18/5.py))

#### 19장 2020년 상반기 삼성전자 기출문제

* [아기 상어](https://www.acmicpc.net/problem/16236) (삼성): [Python 3.7 코드](19/1.py)
* [청소년 상어](https://www.acmicpc.net/problem/19236) (삼성): [Python 3.7 코드](19/2.py)
* [어른 상어](https://www.acmicpc.net/problem/19237) (삼성): [Python 3.7 코드](19/3.py)


#### 부록 B 기타 알고리즘

* 이론
    * 소수 판별: ([Python 3.7 코드](/20/1.py))
    * 에라토스테네스의 체: ([Python 3.7 코드](/20/2.py))
    * 특정한 합을 가지는 부분 연속 수열 찾기 (투 포인터): ([Python 3.7 코드](/20/3.py))
    * 정렬되어 있는 두 리스트 합치기 (투 포인터): [Python 3.7 코드](/20/4.py)
    * 구간 합: ([Python 3.7 코드](/20/5.py))
    * 순열: [Python 3.7 코드](/20/6.py)
    * 조합: [Python 3.7 코드](/20/7.py)
* 실전
    * [소수 구하기](https://www.acmicpc.net/problem/1929) (핵심 유형): [Python 3.7 코드](/20/8.py)
    * [암호 만들기](https://www.acmicpc.net/problem/1759) (핵심 유형): [Python 3.7 코드](/20/9.py)

#### 부록 D 알고리즘 유형별 문제 풀이

### 추가 보충 자료

> 책에서는 자세히 다루지 않지만 독자의 요청으로 추가적으로 제공합니다.

* 트리(Tree)
  * 트리의 순회: ([Python 3.7 코드](/21/1.py))
* 우선순위 큐 (Priority Queue)
  * [우선순위 큐 라이브러리를 활용한 힙 정렬](https://www.acmicpc.net/problem/2751): ([Python 3.7 코드](/21/2.py))
* 바이너리 인덱스 트리 (Binary Indexed Tree, BIT, Fenwick Tree)
  * [구간 합 구하기](https://www.acmicpc.net/problem/2042): ([Python 3.7 코드](/21/3.py))
* 벨만-포드 (Bellman-Ford) 최단 경로 알고리즘
  * [음수 간선이 포함된 그래프에서의 최단 경로 찾기](https://www.acmicpc.net/problem/11657): ([Python 3.7 코드](/21/4.py))
* 최소 공통 조상 (Lowest Common Ancestor, LCA)
  * [LCA 기본](https://www.acmicpc.net/problem/11437): ([Python 3.7 코드](/21/5.py))
  * [LCA 심화](https://www.acmicpc.net/problem/11438): ([Python 3.7 코드](/21/6.py))
