### Tree
- 트리는 널리 사용되는 ADT(Abstract Data Type) 또는 이 ADT를 구현하는 데이터 구조로, 상위 노드가 있는 하위 노드의 루트값과 트리를 사용하여 계층 트리 구조를 시뮬레이션 합니다.
- 트리 데이터 구조는 노드 모음으로 재귀적으로 정의할 수 있습니다. 여기서 각 노드는 노드에 대한 참조 목록(자식 노드)와 함께 값으로 구성된 데이터 구조입니다.
- 아래는 순서가 없는 간단한 트리입니다.

![](https://images.velog.io/images/yujo/post/287bb756-e07b-42c2-8c11-180ff7830ef5/tree.png)

___
### Binary Search Tree
- 이진 검색 트리는 특정 유형의 컨테이너(메모리)에 특정 항목(숫자, 이름 등)을 저장하는 데이터 구조입니다. 항목을 빠르게 조회, 추가, 제거 할 수 있으며 키로 항목을 찾을 수 있는 테이블(이름으로 전화번호 찾기) 등을 구현하는데 사용할 수 있습니다.
- 이진 검색 트리는 키를 정렬 된 순서로 유지하므로 데이터를 조회할 때 이진 탐색의 원칙을 사용할 수 있습니다. 트리에서 키를 찾을 때 루트 -> 트리 방향으로 탐색합니다.
- 아래는 이진 트리의 예입니다.

![](https://images.velog.io/images/yujo/post/73b80af5-edc4-474c-a57c-f7a7cdc59e82/binaryTree.png)

___
### AVL Tree
- AVL트리는 만든 사람의 이름(Adelson-Velsy, Landis)을 따서 AVL트리로 불립니다.
- AVL트리는 자체 균형 이진 검색 트리입니다.
- AVL트리에서 노드의 두 하위 트리의 높이가 하나 이상 다를 경우 속성을 복원하기 위해 재조정이 수행됩니다.
- AVL트리는 조회, 삽입, 삭제의 경우 최악의 경우와 평균의 경우 모두 ```O(log n)```의 시간이 걸립니다.
- 아래는 AVL트리에 여러 요소를 삽입하는 그림입니다.

![](https://images.velog.io/images/yujo/post/8eda1eac-5b01-45c1-bd97-f1b08dfd7e4d/avltree.gif)

___
