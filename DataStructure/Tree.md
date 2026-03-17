# 트리(Tree)

## 개념
- 노드들이 나무 가지처럼 연결된 계층적 자료구조

## 예
- 가족 계보, 연산 수식, 회사 조직 구조도, Heap 포현하기 적합

## 용어 정리
- 노드(Node) : 자료 항목을 가지는 트리를 구성하는 기본 요소
- 근 노드(Root Node) : 트리의 가장 맨 상단에 있는 노드
- 차수(Degree) : 각 노드에서 뻗어나온 가지 수
- 잎사귀 노드(Leaf Node) : 자식이 하나도 없는 노드 (차수가 0인 노드)
- 트리의 깊이(Depth) : 트리에서의 최대 깊이
- 트리의 차수(Degree) : 노드들의 차수 중 최대 차수

# 이진 트리(Binary Tree)

## 개념
- 자식이 둘 이하(차수가 2 이하)인 노드로만 구성된 트리

## 전 이진 트리(Full binary Tree)
- 모든 노드가 0개 또는 2개의 자식노드를 갖는 트리

## 완전 이진 트리(Complete binary Tree)
- 마지막 깊이를 제외한 모든 깊이의 노드가 완전히 채워져 있는 트리

## 이진 트리의 순회
| 종류 | 순서 |
|-----|-------|
| 전위 순회(Pre-order) | Root > Left > Right |
| 중위 순회(In-order | Left > Root > Right |
| 후위 순회(Post-order | Left > Right > Root |

## 이진 수식 트리
- 산술식을 계산하기 위해 이진트리에 기억시키는 방법
  
| 종류 | 순서 |
|-----|-------|
| 전위 순회(Pre-Fix) | Root > Left > Right |
| 중위 순회(In-Fix) | Left > Root > Right |
| 후위 순회(Post-Fix) | Left > Right > Root |

