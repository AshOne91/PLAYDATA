# 딕셔너리 자료형
비 시퀀스 자료형 따라서 인덱스를 갖지 않음
키는 1대 1로 매칭되는 값을 갖음
Key: value -> key-value pair

{} 중괄호로 생성
```
dic_var = {"key":"value"}
dictionary_variable = {key:value, key: value, ...}
```

키는 중복해서 존재하지 않음

## 딕셔너리 자료형 특징
키에 자료형 섞어서 사용가능
단 키에 리스트, 딕셔너리, 집합을 사용할 수 없음
키는 고유한 값을 가지고 있어야함
```
dic_var = {"key":"value", 1:"value2", 1.1:"value3"}
```

값은 모든 자료형을 사용할 수 있음
## 빈 딕셔너리 생성하기
```
x = {}
```
## dict() 함수로 생성하기
```
dic_a = dict(key = "value", key2 = "value2)
```
## dict함수와 시퀀스 객체로 생성하기
```
x = dict([["key", "value"]]);
```

## dict()함수와 zip() 함수로 생성하기
key의 값들을 갖는 리스트
value의 값을 갖는 리스트가 별도로 존재할때
zip함수에 이 각각의 리스트를 넣어주면
튜플로 만들어줌

## 키로 접근하기
dict[키값]

## 키와 값 추가하기
dict_b['new_one'] = 값

## 없는 키에 접근하는 경우 에러남
## 있나 확인 ('key' in dict)

## 특정 키와 값 쌍을 삭제하기
del dict_b['new_one']






