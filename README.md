# Algorithm Study 

#### in Apple Developer Academy @ POSTECH

<br />

## ⏰ Time & Period

- 기간 : 4월 4째주 ~ 6월 4째주 (10주)
- Meeting
  - TEAM A - 월요일 12:40pm (오후 세션 이전)
  - TEAM B (Morning) - 금요일 12:40pm (오후 세션 이전)
  - TEAM B (Afternoon) - 수요일 6:00pm (오후 세션 이후)

<br />

## Participants

- TEAM A
  - 🚩🚩 [Jeckmu / 이재원](https://github.com/220v-K)
  - [Ollie / 김세이]()
  - [Eren / 문희찬]()
  - [Woody / 박현우]()
  - [Sunday / 이선호]()
  - [Poodle / 최어진]()
- TEAM B - Morning
  - 🚩 [Shannon / 이세민]()
  - [Ddan / 박승찬](https://github.com/eemdeeks)
  - [Jerry / 이주환]()
  - [Cyndi / 박지은]()
  - [Lianne / 최예은]()
- TEAM B - Afternoon
  - 🚩 [Swimmer / 황지우]()
  - [Lets / 고석환]()
  - [Soda / 김민]()
  - [Celan / 이승준]()
  - [Benny / 한기백]()
  - [Madeline / 신정연]()

<br />

## Process

### TEAM A

- 주마다 풀 문제를 정합니다.

- 미팅날 까지 풀어옵니다!
- 미팅날 사다리타기🪜로 발표할 문제를 정합니다.

- `for problem in problems_this_week:`
  - 담당한 사람이 문제에 대해 발표합니다. 
    - Ex. 문제에 대한 초견, 생각한 접근법, 실패 과정, 코드 개선 과정, 결과. Time Complexity / Space Complexity 분석. 후기.. etc.
  - 문제에 대한 각자의 후기를 남깁니다.
    - Ex. 이거 이렇게 풀면 더 깔끔해요! / 이거 Time Complexity가 이게 아니라 저렇게 되는 것 같습니당. / 이 문제 너무 어려웠음 ㅠㅠ

### TEAM B (Morning / Afternoon)

- 매 주 공부할(문제를 풀) 주제를 정합니다. (Ex. Stack, Queue, Greedy, Dynamic Programming..)
- 각자 자신에게 맞는 난이도의 문제를 5문제가량 미팅날까지 풀어옵니다!
- `for person in TEAM:`
  - 각자 풀어온 문제들 중 가장 인상 깊었던 문제에 대해 공유합니다.

<br />

## Pull Request & Commit Rule

### PR Rule

- 이 Repository를 각자 Fork합니다.
- 각자의 닉네임으로 Fork한 Repository에서 branching합니다. (Ex. 'Jeckmu' 브랜치 생성)
- 푼 문제(+풀이과정, 설명)을 commit 후 PR 요청을 합니다.
- 각 팀의 미팅 시간에, 각 팀의 리더가 PR을 확인하고 Merge합니다.
- PR Message
  `[N주차] 닉네임` (Ex. `[1주차] Jeckmu`)

### Commit Rule

- 자신의 팀 폴더 - 주차 - (자신의 닉네임) 폴더에 알맞게 commit합니다.

  > 예시
  >
  > ```bash
  > Jeckmu
  > ├── [백준 - 1000] A+B
  > │   ├── [백준 - 1000] A+B.py
  > │   └── [백준 - 1000] 풀이.md
  > ```

- Commit Message
  1. 문제별로 하나씩 commit할 때는 `[N주차] [문제 사이트 - 문제 번호] 문제명`
     - Ex. `[1주차] [백준 - 1000] A+B`
  2. 주차별로 한번에 commit할 때는 `[N주차] 닉네임`
     - Ex. `[1주차] Jeckmu`

<br />

## File Structure (Example)

```bash
.
├── TEAM A
│   ├── Week 1
│   │   ├── Jeckmu
│   │   │   ├── [백준 - 1000] A+B
│   │   │   │   ├── [백준 - 1000] A+B.py
│   │   │   │   └── [백준 - 1000] 풀이.md
│   │   │   └── [백준 - 1005] ACM Craft
│   │   │       ├── [백준 - 1005] ACM Craft.py
│   │   │       └── [백준 - 1005] 풀이.md
│   │   ├── Ollie
│   │   │   ├── ...
│   │   │   └── ...
│   │   ├── ...
│   │   └── ...
│   ├── Week 2
│   │   ├── Jeckmu
│   │   └── ...
│   ├── ...
│   └── ...
├── TEAM B - Afternoon
│   ├── Week 1
│   │   ├── Swimmer
│   │   │   ├── ...
│   │   │   └── ...
│   │   ├── ...
│   │   └── ...
│   ├── ...
│   └── ...
└── TEAM B - Afternoon
    ├── Week 1
    │   ├── Shannon
    │   │   ├── ...
    │   │   └── ...
    │   ├── ...
    │   └── ...
    ├── ...
    └── ...
```

<br />

## History

### TEAM A

<div>
<table>
<tbody>

<tr>
<td><strong>주차</strong></td>
<td><strong>테마</strong></td>
<td><strong>문제 번호 및 이름</strong></td>
</tr>

<!-- 1주차 시작 -->
<tr>
<td>1</td>
<td>백준 - 자유</td>
<td>
  [백준]
   <a target="_blank" href="https://www.acmicpc.net/problem/1647">
      1647. 도시 분할 계획 (Gold IV)
   </a>
   <br />
   [백준]
   <a target="_blank" href="https://www.acmicpc.net/problem/1987">
      1987. 알파벳 (Gold IV)
   </a>
</td>
</tr>
<!-- 1주차 끝 -->

<!-- 2주차 시작 -->
<tr>
<td>2</td>
<td>프로그래머스 -
<strong>2023 KAKAO BLIND RECRUITMENT</strong>
기출문제</td>
<td>
  [프로그래머스]
   <a target="_blank" href="https://school.programmers.co.kr/learn/courses/30/lessons/150369">
      150369. 택배 배달과 수거하기 (Lv.2)
   </a>
   <br />
  [프로그래머스]
   <a target="_blank" href="https://school.programmers.co.kr/learn/courses/30/lessons/150367">
      150367. 표현 가능한 이진트리 (Lv.3)
   </a>
   <br />
  [프로그래머스]
   <a target="_blank" href="https://school.programmers.co.kr/learn/courses/30/lessons/150365">
      150365. 미로 탈출 명령어 (Lv.3)
   </a>
</td>
</tr>
<!-- 2주차 끝 -->

</tbody>
</table>
</div>

### TEAM B

<div>
<table>
<tbody>

<tr>
<td><strong>주차</strong></td>
<td><strong>테마</strong></td>
<td><strong>문제 번호 및 이름</strong></td>
</tr>

<!-- 1주차 시작 -->
<tr>
<td>1</td>
<td>프로그래머스 -
<strong>코딩테스트 고득점 Kit</strong>
</td>
<td>
   <a target="_blank" href="https://school.programmers.co.kr/learn/courses/30/parts/12081">
      스택/큐
   </a>
</td>
</tr>
<!-- 1주차 끝 -->

</tbody>
</table>
</div>
