# 리스트
파이썬 언어에서 가장 유통성 있는 자료형
리스트변수명 = [항목1, 항목2, 항목3, ...]
다른언어의 Array와는 차이가 있음(아무거나 넣을 수 있음)
## 리스트 생성
```python
squares = [1**2, 2**2, 3**2]
print(squares)
print(type(squares))
print(len(squares))
```
## 리스트의 인덱싱과 슬라이싱
```python
print(squares[1:])
print(squares[0])
```
## 리스트의 더하기와 곱하기
```python
print(squares * 3);
print(squares + [4**2, 5**2, 6**2])
squares *= 3
```
## 리스트의 값 변경하기
리스트는 가변
인덱싱과 슬라이싱을 통해서 값을 수정할 수 있음
## 리스트의 크기 계산하기
print(len(lettters))
## 리스트 안에 리스트
```python
a = ['a', 'b', 'c']
n = [1, 2, 3]
x = [a, n]
print(x)
print(x[0])
print(x[0][1])
```
## 리스트에 특정 요소가 있는 지 궁금할 때
print(5 in numbers) => True or False
## 리스트 메소드
append
insert
extend
remove
pop
index
count
sort
reverse
clear
## 리스트 맨 뒤에 요소 추가하기
numbers.append(5)
## 리스트에 요소를 원하는 인덱스에 추가하기
numbers.insert(0, 0) // 0번째 인덱스에 0을 추가
numbers.insert(len(numbers), 0) //마지막 인덱스 + 1에 0을 추가
## 리스트에 리스트를 추가하기
numbers.extend([9, 10, 11])
## 인자와 동일한 값 삭제
list.remove(삭제하고 싶은 요소의 값) //인덱스 순서로
## 맨 마지막 요소를 반환하고 제거하기
list.pop()
## 인자와 같은 값 인덱스 조회
리스트변수.index(찾고자 하는 요소)
## 인자의 갯수
list.count(요소의 값)
## 리스트 요소 정렬하기
list.sort() 오름차순으로 정렬
## 요소를 반대로
list.reverse()
## 리스트 스택처럼 활용









