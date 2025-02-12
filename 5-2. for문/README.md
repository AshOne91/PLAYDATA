# for문
반복적인 일을 처리
## for문과 range() 내장 함수
```
for 요소를 담을 변수 in range(1000):
for 요소를 담을 변수 in 요소를 담은 객체
```
## range()함수
연속되는 숫자 요소들을 만들 때 활용하면 좋음
range변수 = range(시작, 끝, 증감크기)

시작, 증감크기는 생략가능

## range()함수로 list생성하기
list(range(2, 100, 2))

## range() 함수 특징
리스트 처럼 동작하지만 리스트랑 다름
메모리에 할당해놓지 않음

## for문
시퀀스 자료형의 항목들을 순서대로 이터레이션합니다.

## iterable 객체?
반복 가능한이란 사전적의미

## if, for, while문
:이후 선언하고 
다음줄에 들여쓰기해야함


## 시퀀스 객체로 반복하기
```
for _ in [도, 레, 미, 파]
  print(_)
```

## for문으로 시퀀스 객체의 인덱스 루프 테크닉
```
for _ in range(len(scores)):
  print(scores[_]);
```



