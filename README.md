# ⚾ 숫자 야구 게임 (Baseball Game)

사용자가 입력한 숫자와 랜덤으로 생성된 숫자를 비교하여, 스트라이크/볼 여부를 알려주는 숫자 야구 게임입니다.

### 💡 기능 소개
-	랜덤한 4자리 숫자 생성 (중복 없음)
-	사용자의 입력값 유효성 검사
-	결과를 STRIKE / BALL 형태로 출력
-	10회 도전 제한
-	정답 맞출 경우 “홈런!!” 표시
-	정답 미달성 시 시도 횟수 종료 후 정답 공개

### 🛠 기술 스택
-	HTML
-	CSS (reset 포함)
-	JavaScript (Vanilla JS)

### 📁 폴더 구조

```
├── index.html
├── script.js
└── style.css (선택사항)
```

### 🚀 실행 방법
	1.	이 저장소를 클론하거나 파일을 다운로드합니다.
	2.	index.html 파일을 브라우저에서 열면 실행됩니다.

현재 배포는 되어 있지 않으며, 로컬 환경에서 동작합니다.

### 📚 참고 자료 및 개념 정리

#### input type=“number”

[input type 사용 예제](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/number)

- input type number의 min과 max에 대한 이해

#### calc

[calc 사용 예제](https://developer.mozilla.org/en-US/docs/Web/CSS/calc())

- 스타일 사용 시 사용할 수 있는 계산식

#### Object destructuring

[Object 관련링크](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment#object_destructuring)

- Object를 다시 각각의 선언으로 사용할 수 있음

#### new Set()

[Set 사용예제](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Set)
-	새로운 배열을 중복 없이 반환하는 Set()의 사용 예제
-	Set 내 값은 유일해야 하며, 중복된 값은 허용되지 않음

#### parseInt

[parseInt 사용 예제](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/parseInt)

-	parseInt의 기본 radix는 지정되지 않으면 동작이 달라질 수 있음
-	첫 번째 인자를 특정 radix(진수) 값으로 표현한 정수가 반환됨
