## CSS 개념 정리

### 의미
* Cascading Style Sheet
* Cascading: 세부 스타일링의 정의가 있다면 정의를 따르고 없다면 기본 UI 사용
  * Author Style -> User Style -> Browser
  * important: CSS의 나쁜 경우, 가능하면 쓰지 않는 것이 좋음

* Selectors
  * Universal: *
  * Type: Tag
  * ID: #id
  * Class: .class
  * State: :
  * Attribute: []

* Display
  * Block Level: div
  * Inline Level: span
  * 예시: inline-block, block, inline

* Position
  * static: 기본, 위치가 변하지 않음
  * relative: 원래의 위치에서 이동
  * absolute: 박스 안에서 이동
  * fixed: 페이지 안에서 이동
  * sticky: 원래의 위치에 존재하나 스크롤해도 변하지 않음

* Flex Box
  * 박스, 아이템을 행, 열로 자유롭게 배치
  * 1. Container(Box), Item에 지정되는 속성들이 있음
  * 2. Main Axis, Cross Axis: 중심축이 존재하고 수직인 축이 반대축이 됨