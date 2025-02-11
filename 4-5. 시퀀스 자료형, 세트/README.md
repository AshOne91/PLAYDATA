# 세트 자료형
집합과 맥락이 같음
중괄호를 사용해서 생성
세트 자료형은 인덱스를 가지고 있지 않고 키와 값 역할 모두 한다.
순서가 없음
set_variable = {키1, 키2, 키3}
## 빈 세트 생성하기
x = set() #해당 함수로만 생성가능
#빈 중괄호는 딕셔너리가 생성
## 특징
동일한 요소 X
## 세트에 값 넣는 방법
세트 자료형.add(요소)
## 요소 삭제하기
세트자료형.remove(요소)
요소가 없으면 에러가 나옴

세트자료형.discard(요소)
요소가 없어도 에러가 안나옴

## 요소 임의 삭제
세트자료형.pop()
순서가 보장되지 않음
요소가 없다면 KeyError를 발생

## 전체 요소 삭제
clear()

## 요소 전체 크기
len(set_var)

## 합집합
set.union(a, b)

## 교집합
a & b
## 차집합
set.difference(a, b)
## update() 혹은 |=
## difference_update() 혹은 -=
## 부분집합 issubset() True Or False
## ==같다
## 겹치지 않는지 확인 isdisjoint()






