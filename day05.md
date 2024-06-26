# Flutter day 05
1. Widget
    - 독립적으로 실행되는 작은 프로그램
    - 주로 바탕화면 등에서 날씨나 뉴스, 생활정보 등을 보여줌
    - 그래픽이나 데이터 요소를 처리하는 함수를 가지고 있음

2. Widget을 이루고 있는 요소, 담당
    - UI를 만들고 구성하는 모든 기본 단위 요소
    - 눈에 보이지 않는 요소들까지 위젯
    - 모든 것이 위젯이다 --> 모든 버튼, 마진 등

3. Widget의 종류
    1. Stateless Widget
        - 이전 상호작용의 어떠한 값도 저장하지 않음
        - 상태가 없는 정적인 위젯
        - 스크린상에 존재만 할 뿐 아무것도 하지 않음
        - 어떠한 실시간 데이터도 저장하지 않음<br/>
        MyApp - Material App - My HomePage - Scaffold - Appbar - Text

    2. Stateful Widget
        - Value값을 지속적으로 추적 보존
        - 상태가 있는 동적인 위젯
        - 사용자의 interaction에 따라서 모양이 바뀜
        - 데이터를 받게 되었을 때도 모양이 바뀜 ( ex : input )


    3. Inherited Widget

4. Flutter Widget tree
    - Widget들은 tree구조로 정리될 수 있음
    - 한 Widget내에 얼마든지 다른 Widget들이 포함될 수 있음
    - Widget은 부모 위젯과 자식 위젯으로 구성
    - Parent Widget을 Widget Container라고 부르기도 함
    