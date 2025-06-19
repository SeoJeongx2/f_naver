**✅ CSS Flexbox 모든 주요 속성 정리**

### 1. 부모 요소 (Flex Container)에서 사용하는 속성

| 속성                | 값                             | 설명 |
|---------------------|----------------------------------|------|
| `display`           | `flex`, `inline-flex`           | Flexbox 컨테이너로 설정 |
| `flex-direction`    | `row`, `row-reverse`, `column`, `column-reverse` | 주 축 방향 설정 |
| `flex-wrap`         | `nowrap`, `wrap`, `wrap-reverse` | 줄 바꿈 여부 설정 |
| `flex-flow`         | `<flex-direction> <flex-wrap>`  | 위 2개 속성의 단축형 |
| `justify-content`   | `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly` | 주 축 정렬 |
| `align-items`       | `stretch`, `flex-start`, `flex-end`, `center`, `baseline` | 교차 축(세로축 등) 정렬 |
| `align-content`     | `stretch`, `flex-start`, `flex-end`, `center`, `space-between`, `space-around` | 여러 줄의 교차 축 정렬 |


### 2. 자식 요소 (Flex Item)에서 사용하는 속성

| 속성          | 값                     | 설명 |
|---------------|--------------------------|------|
| `flex-grow`   | 숫자 (0 이상)            | 남는 공간을 비율대로 분배 |
| `flex-shrink` | 숫자 (0 이상)            | 공간이 부족할 때 줄어드는 비율 |
| `flex-basis`  | 길이, `auto`              | 초기 크기 설정 |
| `flex`        | `flex-grow flex-shrink flex-basis` | 위 3개 속성의 단축형 |
| `align-self`  | `auto`, `flex-start`, `flex-end`, `center`, `baseline`, `stretch` | 개별 아이템 교차 축 정렬 |
| `order`       | 숫자                    | 아이템 순서 재배열 |


---

**✅ CSS Grid 모든 주요 속성 정리**

### 1. 부모 요소 (Grid Container)에서 사용하는 속성

| 속성                      | 값 예시                        | 설명 |
|---------------------------|---------------------------------|------|
| `display`                 | `grid`, `inline-grid`           | Grid 컨테이너 설정 |
| `grid-template-columns`   | `200px 1fr 1fr`, `repeat(3, 1fr)` | 열 정의 |
| `grid-template-rows`      | `auto 100px`, `repeat(2, 1fr)`  | 행 정의 |
| `grid-template-areas`     | 문자열 영역 이름               | 영역 정의 |
| `grid-template`           | `grid-template-rows / columns`  | 행/열 정의 통합 |
| `grid-auto-columns`       | `100px`, `auto`                 | 자동 생성 열의 크기 |
| `grid-auto-rows`          | `min-content`, `1fr`            | 자동 생성 행의 크기 |
| `grid-auto-flow`          | `row`, `column`, `dense`       | 아이템 자동 배치 방향 |
| `gap` / `row-gap`, `column-gap` | `20px`, `10px 15px`     | 행/열 간격 설정 |
| `justify-content`         | `start`, `center`, `end`, `space-between`, 등 | 전체 콘텐츠 수평 정렬 |
| `align-content`           | `start`, `center`, `stretch` 등 | 전체 콘텐츠 수직 정렬 |
| `justify-items`           | `start`, `center`, `end`, `stretch` | 셀 내 아이템 수평 정렬 |
| `align-items`             | `start`, `center`, `end`, `stretch` | 셀 내 아이템 수직 정렬 |


### 2. 자식 요소 (Grid Item)에서 사용하는 속성

| 속성               | 값 예시                          | 설명 |
|--------------------|-----------------------------------|------|
| `grid-column`      | `1 / 3`, `span 2`                 | 열 위치 지정 |
| `grid-row`         | `2 / 4`, `span 3`                 | 행 위치 지정 |
| `grid-area`        | 이름 또는 `row-start / col-start / row-end / col-end` | 위치 또는 영역 이름 지정 |
| `justify-self`     | `start`, `center`, `end`, `stretch` | 셀 안에서의 수평 정렬 |
| `align-self`       | `start`, `center`, `end`, `stretch` | 셀 안에서의 수직 정렬 |
| `place-self`       | `align-self justify-self`         | 정렬 속성 통합형 |
| `z-index`          | 숫자                             | 겹치는 순서 지정 |


---

필요 시 각 속성에 대한 시각 예제, 데모, 실전 코딩 템플릿도 제공 가능합니다.
