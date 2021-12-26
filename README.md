

# coddingBuddy
코딩버디 스터디 과제 업데이트, 코드리뷰

과제 목록
==========
## 제어문
- 과제0. Junit 5 학습하세요
    - 인텔리제이에서 JUnit 5로 테스트 코드 작성하는 방법에 익숙해 질것.
    - 이미 JUnit 알고 계신분들은 다른 것 아무거나!
    - 더자바, 테스트 강의 있으니 참고 https://www.inflearn.com/course/the-java-application-test?inst=86d1fbb8
- 과제 1. live-study 대시 보드를 만드는 코드를 작성하세요.
    - 깃헙 이슈 1번부터 18번까지 댓글을 순회하며 댓글을 남긴 사용자를 체크할 것
    - 참여율을 계산하세요. 총 18회 중에 몇 %를 참여했는지 소숫점 두자리 까지 보여줄 것
    - Github 자바 라이브러리를 사용하면 편리합니다.
    - 깃헙 API를 익명으로 호출하는데 제한이 있기 때무에 본인의 깃헙 프로젝트에 이슈를 만들고 테스트를 하시면 더 자주 테스트 할 수 있습니다. https://github-api.kohsuke.org/
- 과제 2. LinkedList 를 구현하세요.
    - LinkedList에 대해 공부하세요.
    - 정수를 저장하는 ListNode 클래스를 구현하세요.
    - ListNode add(ListNode head, ListNode nodeToAdd, int position)를 구현하세요.
    - ListNode remove(ListNode head, int positionToRemove)를 구현하세요.
    - boolean contains(ListNode head, ListNode nodeTocheck)를 구현하세요.
- 과제 3. Stack을 구현하세요
    - int 배열을 사용해서 정수를 저장하는 Stack을 구현하세요
    - void push(int data)를 구현하세요.
- int pop() 을 구현하세요.
- 과제 4. 앞서 만든 ListNode를 사용해서 Stack을 구현하세요.
    - ListNode head를 가지고 있는 ListNodeStack클래스를 구현하세요.
    - void push(int data) 를 구현하세요.
- int pop()을 구현하세요.
- 과제 5 . Queue를 구현하세요.
    - 배열을 사용해서 한번
    - ListNode를 사용해서 한번.

## 클래스
- int 값을 가지고 있는 이진 트리를 나타내는 Node라는 클래스를 정의하세요.
- int value, Node left,right 를 가지고 있어야 합니다.
- BinrayTree라는 클래스를 정의하고 주어진 노드를 기준으로 출력하는 bfs(Node node)와 dfs(Node node) 메소드를 구현하세요.
- DFS는 왼쪽,루트,오른쪽 순으로 순회하세요.
