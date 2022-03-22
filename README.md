# Go: 백준 나만의 문제풀이 키워드

---

#### 1001~2000

- `bj1003`: 다이나믹 프로그래밍 - 피보나치 수열이라 생각보다 간단하다
- `bj1010`: 다이나믹 프로그래밍 - 미리 모든 경우의 값을 구해놓고 해당하는 값을 찾는 것이 빠르다
- `bj1011`: 제곱근
- `bj1012`: 그래프 탐색
- `bj1021`: 자료 구조 - 덱
- `bj1026`: a와 b를 정렬, (a의 가장 작은 수 \* b의 가장 큰 수)를 반복하면 최솟값을 구할 수 있다
- `bj1037`: 정수론 - 약수들 중 가장 작은 수와 가장 큰 수의 곱이 원래 수 N
- `bj1038`: 브루트포스 알고리즘 - 큐 사용하기
- `bj1057`: 브루트포스 알고리즘
- `bj1064`: 기하학 - 피타고라스 정리
- `bj1068`: 그래프 탐색 - 너비 우선 탐색
- `bj1072`: 이분 탐색 - Z가 99 이상인 경우 더이상 커질 수 없으므로 이를 제외하고 탐색한다
- `bj1074`: 분할 정복
- `bj1075`
- `bj1094`
- `bj1100`: 배열, 슬라이스, strings 패키지 - 문자열 분할
- `bj1106`: 다이나믹 프로그래밍 - '적어도'라는 표현을 사용하므로 초과되는 경우의 수도 고려해야 한다
- `bj1107`: 브루트포스 알고리즘
- `bj1110`: 반복문
- `bj1149`: 다이나믹 프로그래밍
- `bj1152`: strings 패키지 - Split(), TrimSpace()
- `bj1153`: 에라토스테네스의 체
- `bj1157`
- `bj1174`: 브루트포스 알고리즘 - 1038번과 유사
- `bj1181`: sort 패키지 - Slice() 함수의 두번째 인수로 커스텀 정렬 함수 리터럴
- `bj1182`: 백트래킹, 브루트포스 알고리즘
- `bj1188`: 유클리드 호제법
- `bj1197`: 최소 신장 트리 - 크루스칼 알고리즘
- `bj1205`: 조건문을 잘 활용하자
- `bj1225`: 반복문, strconv 패키지 - string(byte타입)을 정수로 변환
- `bj1240`: 그래프 탐색 - 깊이 우선 탐색
- `bj1253`: 두 포인터
- `bj1259`
- `bj1260`: 깊이 우선 탐색, 너비 우선 탐색 - 정점 번호가 작은 것을 먼저 방문한다는 조건에 주의
- `bj1267`
- `bj1271`: math/big 패키지 - big numbers
- `bj1284`: 포인터 슬라이스, bufio 패키지 - 스캐너
- `bj1297`: 피타고라스의 정리
- `bj1309`: 다이나믹 프로그래밍 - dp[i] = dp[i-1]\*2 + dp[i-2]
- `bj1315`: 다이나믹 프로그래밍 - 맵
- `bj1325`: 그래프 탐색 - 깊이 우선 탐색
- `bj1343`: strings 패키지 - Contains()로 확인하고 ReplaceAll()로 변환
- `bj1357`: strings 패키지 - Builder 타입으로 문자열 역순으로 붙이기
- `bj1371`: ioutil 패키지를 사용해 한 번에 읽은 뒤에 쪼개기
- `bj1389`: 그래프 탐색, 너비 우선 탐색 - 플로이드 와샬을 알면 더 쉽게 풀 수 있는 문제인 것 같다
- `bj1439`: strings 패키지 - builder 타입
- `bj1448`: 그리디 알고리즘 - 삼각형의 가장 큰 변의 길이 < 나머지 변의 길이의 합인데 모든 경우를 구하려면 시간초과 발생, n항 < n-1항 + n-2 항인 경우만 탐색하는 것이 최적해
- `bj1449`: 그리디 알고리즘 - 오름차 순으로 정렬
- `bj1453`
- `bj1463`: 다이나믹 프로그래밍 - 분할 & 정복이라는 것은 알고 있지만, 아직은 너무 어려운듯
- `bj1475`: 0부터 9까지의 값이 반복되므로 배열의 인덱스를 활용하여 해당 인덱스의 값을 증가
- `bj1476`: 15의 배수에 e를 더한 값을 연도로 가정하고 반복하면 빠르게 최솟값을 찾을 수 있다
- `bj1484`: 두 포인터
- `bj1495`: 다이나믹 프로그래밍
- `bj1541`: 그리디 알고리즘
- `bj1547`: bufio 패키지 - 스캐너, strings 패키지 - Split(), 포인터 변수
- `bj1620`: 자료 구조 - 맵
- `bj1629`: 분할 정복 - 거듭 제곱
- `bj1647`: 최소 신장 트리 - 크루스칼 알고리즘
- `bj1654`: 이분탐색, 시작을 0으로 시작하면 **런타임 에러(DivideByZero)** 발생
- `bj1660`: 다이나믹 프로그래밍
- `bj1676`: 끝에 0이 온다는 것은 10으로 나누어 떨어진다는 것. 2와 5의 개수를 구해서 작은 것을 출력하면 0의 개수를 구할 수 있다
- `bj1697`: 그래프 이론 - 깊이 우선 탐색
- `bj1699`: 다이나믹 프로그래밍
- `bj1735`: 정수론 - 최대공약수
- `bj1756`: 백트래킹
- `bj1758`: 그리디 알고리즘 - 내림차순으로 정렬하면 최적해를 구할 수 있다
- `bj1764`: 단일 for 반복문 내에서 if문으로 분기
- `bj1769`: 백만 자리의 숫자를 처리하는 방법 필요 -> 처음에만 바이트 타입 슬라이스로 연산
- `bj1780`: 분할 정복
- `bj1788`: 다이나믹 프로그래밍 - n이 음수인데 짝수인 경우만 결과가 음수이다
- `bj1789`: 그리디 알고리즘 - 가장 작은 수 ~ 2를 곱했을 때 남은 수보다 크거나 같아졌을 때 까지
- `bj1850`: 정수론
- `bj1874`: 자료구조 - 스택
- `bj1904`: 다이나믹 프로그래밍 - dp[i] = (dp[i - 1] + dp[i - 2]) % 15746
- `bj1912`: 연속된다는 것은 부분적으로도 연속한다는 의미
- `bj1920`: 슬라이스를 사용하면 시간 초과, 맵을 사용해야 빠르다
- `bj1922`: 최소 신장 트리
- `bj1927`: 자료 구조 - 최소 힙
- `bj1929`: 소수 판별, m이 1일 경우 1은 소수가 아니므로 2부터 판별 시작
- `bj1931`: 그리디 알고리즘 - 끝나는 시간을 오름차순으로 정렬하면 최적해를 빠르게 찾을 수 있다
- `bj1932`: 다이나믹 프로그래밍 - 위에서부터 차례대로 누적되는 합의 최댓값을 구하면 된다
- `bj1934`: 최대공약수, 최소공배수
- `bj1964`: 계차수열
- `bj1965`: 다이나믹 프로그래밍
- `bj1966`: 중요도에 따라 정렬하는 과정, 인덱스의 변화, 그리고 인쇄되는 순서를 처음부터 모두 계산하였다
- `bj1978`: 소수를 판별하기 위해 나누는 수를 제곱근 이하로 하면 훨씬 빠르다
- `bj1990`: 소수 판정, 팰린드롬 수 - 최적화 필요
- `bj1991`: 트리 - 전위 순회, 중위 순회, 후위 순회
- `bj1992`: 분할 정복

#### 2001~3000

- `bj2012`: 그리디 알고리즘 - 슬라이스를 오름차순으로 정렬하면 최적의 해를 구할 수 있다
- `bj2023`: 소수 판정
- `bj2052`: 실수 정밀도
- `bj2108`: 배열을 정렬하여 사용, 두번째 최빈값을 찾는데 오래 걸리는 코드
- `bj2110`: 이분탐색
- `bj2230`: 두 포인터 알고리즘
- `bj2133`: 다이나믹 프로그래밍
- `bj2156`: 다이나믹 프로그래밍
- `bj2164`: 2의 거듭제곱의 구간 사이에 짝수가 반복되는 패턴이 존재
- `bj2170`: 정렬, 스위핑
- `bj2178`: 그래프 탐색 - 너비 우선 탐색
- `bj2217`: 그리디 알고리즘 - 가장 약한 로프 \_ 전체 로프 수 ~ 가장 강한 로프
- `bj2225`: 다이나믹 프로그래밍 - 테이블로 정리하다가 찾은 규칙: dp[i-1][j] + dp[i][j-1]
- `bj2229`: 다이나믹 프로그래밍
- `bj2231`: 백만 이하의 각 자릿수를 다 더해도 최대 54이기 때문에 적당히 n - 50에서 반복하면 빠르게 찾을 수 있다
- `bj2292`: 계차수열
- `bj2293`: 다이나믹 프로그래밍
- `bj2294`: 다이나믹 프로그래밍
- `bj2338`: math/big 패키지 - big numbers
- `bj2407`: 다이나믹 프로그래밍 - 조합을 구할 때 [][]\*big.Int 2차원 배열을 사용해 큰 수의 연산, big 패키지의 Binomial() 함수를 사용해도 같은 결과
- `bj2410`: 다이나믹 프로그래밍
- `bj2417`: math 패키지, Sqrt(), Floor()
- `bj2436`: 유클리드 호제법, 브루트포스 알고리즘
- `bj2468`: 그래프 탐색 - 깊이 우선 탐색: '아무 지역도 물에 잠기지 않을 수 있다'는 조건에 주의
- `bj2470`: 두 포인터 알고리즘 - 6467번 문제 + 오름차순 정렬
- `bj2476`
- `bj2490`: strings 패키지 - Count() 특정 문자열이 포함되어 있는지 확인
- `bj2491`: 다이나믹 프로그래밍 - 증가하는 경우와 감소하는 경우를 따로 배열에 저장하고 최댓값 비교
- `bj2493`: 자료구조 - 스택
- `bj2502`: 다이나믹 프로그래밍 - 주석 참고
- `bj2506`
- `bj2512`: 이분 탐색 - 탐색 범위를 정확히 파악하자
- `bj2576`
- `bj2579`: 다이나믹 프로그래밍 - 마지막 계단을 반드시 밟아야 한다는 점을 주의
- `bj2581`: m 이상 n 이하 소수 구하기
- `bj2606`: 너비우선탐색 - 아직 이해도가 떨어져서 코드가 지저분함
- `bj2609`: 최대공약수, 최소공배수
- `bj2624`: 다이나믹 프로그래밍
- `bj2630`: 분할 정복
- `bj2631`: 다이나믹 프로그래밍 - 가장 긴 부분 증가 수열
- `bj2667`: 그래프 탐색 - 깊이 우선 탐색
- `bj2670`: 다이나믹 프로그래밍
- `bj2675`: bufio 패키지 - Writer 객체 활용
- `bj2688`: 다이나믹 프로그래밍 - dp[i][j] = dp[i-1][j] + dp[i][j+1]
- `bj2705`: 다이나믹 프로그래밍 - dp[i]는 1부터 i/2번째 항까지의 합 + 1
- `bj2721`: 삼각수 - n\*(n+1)/2
- `bj2739`
- `bj2742`: bufio 패키지 - Writer 타입 객체 활용
- `bj2747`: 피보나치 수열 반복문
- `bj2748`: 피보나치 수열 반복문
- `bj2750`: sort 패키지 - 문자열로 정렬하면 음수도 오름차순이 되므로 정수로 바꾸자
- `bj2751`: 오름차순 정렬 및 출력, 최적화 필요
- `bj2752`: sort 패키지 - sort.Ints() 정수타입 슬라이스 정렬
- `bj2775`
- `bj2776`: 이분 탐색
- `bj2780`: 다이나믹 프로그래밍 - 비밀번호가 누적되어 연결된다고 생각하기
- `bj2790`: 정렬
- `bj2792`: 이분 탐색
- `bj2798`: 3중 for문으로 모든 경우의 수를 탐색
- `bj2805`: 이분 탐색 - 적어도 M미터 이므로 M미터 미만으로 나오지 않는 모든 경우를 탐색
- `bj2839`: 그리디 알고리즘
- `bj2845`
- `bj2847`: 그리디 알고리즘
- `bj2869`
- `bj2908`: strings 패키지 - Compare() 함수로 문자열 비교
- `bj2914`
- `bj2947`: 슬라이스로 값 비교
- `bj2960`: 에라토스테네스의 체 - 이 문제는 소수인지 여부는 불필요하고 지워지는 순서만 카운팅
- `bj2986`: 정수론

#### 3001~4000

- `bj3003`
- `bj3036`: 정수론 - 최대공약수
- `bj3052`: map으로 중복되는 나머지 제외
- `bj3053`: 기하학 - 택시 기하학에 대해 처음 들어봤다
- `bj3273`: 정렬 - a[i] + a[j] = x를 찾아야 하는데 시간이 덜 걸리는 방법이 필요할 것 같다. 두 포인터?

#### 4001~5000

- `bj4097`: 다이나믹 프로그래밍
- `bj4153`: 직각삼각형 - 피타고라스의 정리
- `bj4386`: 최소 신장 트리 - 크루스칼 알고리즘
- `bj4796`: 나머지 연산 예외 처리
- `bj4811`: 다이나믹 프로그래밍
- `bj4883`: 다이나믹 프로그래밍 - 정점의 수가 고정되어 있으므로 어떻게 이동하는지를 파악하면 된다
- `bj4949`: 괄호의 좌,우가 매칭이 되는지 일일이 체크

#### 5001~6000

- `bj5073`: 기하학 - 삼각형의 조건: 가장 긴 변의 길이 < 나머지 두 변의 길이의 합
- `bj5522`: 반복문
- `bj5525-1`: 문자열 - 다이나믹 프로그래밍을 풀어봤지만 부분 점수에서 런타임 오류로 감점. 왜 런타임 오류?
- `bj5554`
- `bj5557`: 다이나믹 프로그래밍
- `bj5582`: 다이나믹 프로그래밍 - dp[i][j] = dp[i - 1][j - 1] + 1

#### 6001~7000

- `bj6064`: 정수론, 중국인의 나머지 정리는 아직 이해가 안됨
- `bj6198`: 자료구조 - 스택
- `bj6322`: 기하학 - 피타고라스 정리
- `bj6502`: 기하학 - 피타고라스 정리: 피자의 대각선 길이 <= 테이블의 지름

#### 7001~8000

- `bj7510`: 기하학 - 피타고라스의 정리
- `bj7568`: 2차원 배열에 값을 저장하고 모두 비교 해보기
- `bj7576`: 그래프 탐색 - 너비 우선 탐색
- `bj7785`: 맵, 역순 출력

#### 8001~9000

- `bj8094`: 다이나믹 프로그래밍 - n항 = n-1항 + n-2항
- `bj8958`

#### 9001~10000

- `bj9012`: 예외 처리 - '('없이 ')'로만 시작하는 경우
- `bj9084`: 다이나믹 프로그래밍
- `bj9095`: 다이낭믹 프로그래밍 - n번째 항 = n-1 항 + n-2 항 + n-3 항
- `bj9009`: 그리디 알고리즘 - n보다 작은 피보나치 수 중에 가장 큰 수를 빼다보면 최적해를 찾을 수 있다
- `bj9237`: 그리디 알고리즘 - 가장 오래 걸리는 나무부터 심는 것이 최적해
- `bj9251`: 다이나믹 프로그래밍
- `bj9372`: 깊이 우선 탐색 | 신장 트리
- `bj9375`: map을 사용해야 하는 문제 - (의상의 개수 + 의상을 입지 않는 경우)를 곱해주고 의상을 모두 입지 않은 경우 1을 빼준다
- `bj9461`: 다이나믹 프로그래밍 - dp[i] = dp[i-2] + dp[i-3]
- `bj9465`: 다이나믹 프로그래밍
- `bj9507`: 다이나믹 프로그래밍
- `bj9613`: 정수론 - 최대공약수
- `bj9655`: 게임 이론
- `bj9656`: 게임 이론, 다이나믹 프로그래밍
- `bj9657`: 게임 이론, 다이나믹 프로그래밍
- `bj9658`: 게임 이론, 다이나믹 프로그래밍
- `bj9660`: 게임 이론
- `bj9711`: 다이나믹 프로그래밍, 큰 수
- `bj9764`: 다이나믹 프로그래밍

#### 10001~11000

- `bj10026`: 그래프 탐색 - 깊이 우선 탐색
- `bj10211`: 다이나믹 프로그래밍 - 이전 항과 더해서 자기 자신보다 작아지지 않으면 누적해서 더한다
- `bj10610`: string을 변환하면 실패하고, byte를 변환하면 실행되는 이유가 뭔지 모르겠다
- `bj10699`: time 패키지 - 년월일 구하기, YYYY-MM-DD 출력 포맷 지정
- `bj10773`
- `bj10809`: byte 연산으로 인덱스 구하기
- `bj10814`: sort 패키지 - SliceStable() 함수를 사용해 구조체를 나이순으로 안정 정렬
- `bj10815`: 이분 탐색 - 탐색 대상이 되는 슬라이스 a를 오름차순으로 정렬
- `bj10816`: map을 사용해 숫자 카드 탐색
- `bj10826`: 다이나믹 프로그래밍 - big/math 패키지로 피보나치 수열의 큰 수의 연산 처리
- `bj10828`: 자료구조 - 슬라이스로 스택 구현
- `bj10844`: 다이나믹 프로그래밍 - 계단 수의 다음 수로 0과 9가 오는 경우를 주의
- `bj10845`: 자료구조 - 슬라이스로 큐 구현
- `bj10866`: 자료구조 - 슬라이스로 덱 구현
- `bj10989`

#### 11001~12000

- `bj11047`: greedy - 큰 수부터 차례대로 전부 나눠보자
- `bj11048`: 다이나믹 프로그래밍
- `bj11050`: 이항 계수 - n! / (k! * (n-k)!)
- `bj11051`: 다이나믹 프로그래밍 - 조합
- `bj11052`: 다이나믹 프로그래밍
- `bj11053`: 다이나믹 프로그래밍
- `bj11055`: 다이나믹 프로그래밍
- `bj11057`: 다이나믹 프로그래밍 - 9 뒤에는 9만 올 수 있음, 9부터 0까지 역순으로 누적된 값을 초기화
- `bj11058`: 다이나믹 프로그래밍
- `bj11060`: 다이나믹 프로그래밍
- `bj11279`: 자료구조 - 최대 힙
- `bj11283`: unicode/utf8 패키지 - []byte 타입으로 입력을 받아 rune 타입으로 변환
- `bj11286`: 자료구조 - 절댓값 힙
- `bj11399`: 그리디 알고리즘 - 오름차순으로 정렬하면 최적해를 구할 수 있다
- `bj11403`: 그래프 탐색 - 플로이드 와샬
- `bj11501`: 그리디 알고리즘 - 주석 참고
- `bj11502`: 에라토스테네스의 체, 브루트포스 알고리즘 - 입력보다 작은 소수들을 먼저 구하고 가능한 경우의 수를 탐색
- `bj11508`: 그리디 알고리즘 - 오름차 순으로 정렬하여 가장 큰 수 2개 다음에 오는 수는 공짜로 계산하면 최적해를 찾을 수 있다
- `bj11568`: 다이나믹 프로그래밍
- `bj11650`: sort 패키지 - 구조체 슬라이스 커스텀 정렬
- `bj11651`: sort 패키지 - 구조체 슬라이스 커스텀 정렬
- `bj11652`: 맵을 활용하여 입력값의 개수를 저장
- `bj11653`
- `bj11659`: 누적합 - i~j까지의 합 = j까지의 누적합 - (i-1)까지의 누적합
- `bj11660`: 다이나믹 프로그래밍 - 누적 합
- `bj11720`: byte 타입으로 읽어서 숫자의 합 구하기
- `bj11722`: 다이나믹 프로그래밍 - 11053, 11055와 유사한 문제
- `bj11723`: 배열 집합 연산 - 비트 마스킹을 알면 더 빠른 연산을 구현할 수 있을 것 같다
- `bj11724`: 그래프 탐색 - 깊이 우선 탐색
- `bj11725`: 그래프 탐색 - 너비 우선 탐색
- `bj11726`: 다이나믹 프로그래밍 - dp[i] = (dp[i-1] + dp[i-2]) % 10007
- `bj11727`: 다이나믹 프로그래밍 - dp[i] = (dp[i-1] + 2\*dp[i-2]) % 10007
- `bj11866`: 요세푸스 문제 - 배열과 인덱스를 활용하자
- `bj11867`: 게임 이론
- `bj11880`: 기하학 - 피타고라스 정리

#### 12001~13000

- `bj12026`: 다이나믹 프로그래밍
- `bj12851`: 다이나믹 프로그래밍 - 숨바꼭질: 메모리 128152KB, 시간 1032ms 효율이 많이 안좋은 코드
- `bj12852`: 다이나믹 프로그래밍 - 너비 우선 탐색
- `bj12865`: 다이나믹 프로그래밍 - 2차원 배열 사용
- `bj12904`: 그리디 알고리즘

#### 13001~14000

- `bj13164`: 그리디 알고리즘
- `bj13241`: 정수론 - 최대공약수, 최소공배수
- `bj13398`: 다이나믹 프로그래밍
- `bj13549`: 다이나믹 프로그래밍: 최적화 필요
- `bj13699`: 다이나믹 프로그래밍

#### 14001~15000

- `bj14231`: 다이나믹 프로그래밍
- `bj14241`: 그리디 알고리즘 - 오름차순으로 정렬하면 최적해를 찾을 수 있다
- `bj14425`: 문자열, 맵
- `bj14430`: 다이나믹 프로그래밍 - dp[i][j - 1]과 dp[i - 1][j] 중 큰 수와 더하면서 진행
- `bj14494`: 다이나믹 프로그래밍 - dp[i][j] = dp[i][j-1] + dp[i-1][j] + dp[i-1][j-1]
- `bj14495`: 다이나믹 프로그래밍
- `bj14501`: 다이나믹 프로그래밍
- `bj14567`: 위상 정렬 - 깊이 우선 탐색
- `bj14606`: 다이나믹 프로그래밍 - dp[i] = dp[i/2] + dp[i-(i/2)] + (i/2)\*(i-(i/2))
- `bj14607`: 다이나믹 프로그래밍이지만 시간 초과가 발생하는 문제, 규칙을 찾아야 한다
- `bj14650`: 다이나믹 프로그래밍
- `bj14651`: 다이나믹 프로그래밍
- `bj14728`: 다이나믹 프로그래밍, 배낭 문제
- `bj14916`: 다이나믹 프로그래밍
- `bj14940`: 그래프 이론 - 너비 우선 탐색

#### 15001~16000

- `bj15486`: 다이나믹 프로그래밍 - 주석 참고
- `bj15489`: 다이나믹 프로그래밍 - dp[i][j] = dp[i-1][j-1] + dp[i-1][j]
- `bj15645`: 다이나믹 프로그래밍
- `bj15650`: 백트래킹
- `bj15652`: 백트래킹
- `bj15654`: 백트래킹
- `bj15657`: 백트래킹
- `bj15663`: 백트래킹
- `bj15666`: 백트래킹
- `bj15686`: 브루트포스 알고리즘
- `bj15817`: 다이나믹 프로그래밍
- `bj15829`: 해시 함수 - 나머지 연산
- `bj15903`: 그리디 알고리즘 - 오름차순으로 정렬해 인덱스가 0과 1인 최솟값끼리 더해주는 것을 반복하면 최적해를 찾을 수 있다
- `bj15922`: 스위핑 - 2170번 문제와 동일
- `bj15988`: 다이나믹 프로그래밍 - dp[i] = dp[i-1] + dp[i-2] + dp[i-3]
- `bj15989`: 다이나믹 프로그래밍 - 2차원 배열로 각각 1, 2, 3으로 시작하는 합의 갯수를 구한다
- `bj15990`: 다이나믹 프로그래밍 - 2차원 배열로 각각 1, 2, 3으로 시작하는 합의 갯수를 구한다
- `bj15991`: 다이나믹 프로그래밍 - dp[i] = dp[i-2] + dp[i-4] + dp[i-6]
- `bj15992`: 다이나믹 프로그래밍 - dp[i][j] = dp[i-3][j-1] + dp[i-2][j-1] + dp[i-1][j-1]
- `bj15993`: 다이나믹 프로그래밍

#### 16001~17000

- `bj16194`: 다이나믹 프로그래밍 - dp[i] = dp[j] + dp[i-j] (j는 1부터 i-1까지)
- `bj16401`: 이분 탐색 - 시작 1, 끝 배열의 최댓값
- `bj16435`: 그리디 알고리즘 - 오름차순으로 정렬하여 비교
- `bj16928`: 그래프 탐색 - 너비 우선 탐색
- `bj16953`: 그래프 탐색 - 너비 우선 탐색

#### 17001~18000

- `bj17175`: 다이나믹 프로그래밍 - 피보나치 함수가 호출되는 횟수는 n-1항과 n-2항을 더한 값에 1을 더해주면 된다
- `bj17212`: 다이나믹 프로그래밍 - i-2항, i-5항, i-7항과 비교
- `bj17219`: 맵을 사용하여 탐색
- `bj17286`: 기하학, 브루트포스
- `bj17291`: 다이나믹 프로그래밍 - 주석 참고
- `bj17626`: 다이나믹 프로그래밍 - 1699번과 같은 문제, dp[i - j*j]와 비교하며 최솟값을 찾는다

#### 18001~19000

- `bj18111`: 브루트포스 알고리즘
- `bj18258`: 자료 구조 - 큐 10845번과 같은 문제, 전체 명령의 수가 1만에서 2백만으로 늘어났지만 큰 변화는 없다
- `bj18310`: 그리디 알고리즘 - 최적해로 짝수일 때, 홀수일 때 나눠서 중간값을 구한다
- `bj18353`: 다이나믹 프로그래밍 - 가장 긴 감소하는 부분 수열
- `bj18870`: 정렬 - 좌표 압축

#### 19001~20000

- `bj19621`: 다이나믹 프로그래밍 - i-2번째 항까지의 최댓값 dp[j]와 i번째 항의 이용자 수를 더한다
- `bj19947`: 다이나믹 프로그래밍

#### 20001~21000

- `bj20500`: 다이나믹 프로그래밍

#### 2100`~22000

- `bj21317`: 다이나믹 프로그래밍 - DFS로 풀 수 있는 문제