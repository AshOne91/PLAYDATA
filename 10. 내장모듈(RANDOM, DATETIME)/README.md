## random 라이브러리
표준 라이브러리
PSL이라 부름

## random.random()
```
import random
num = random.random()
print(num)
```
## random.randint(1, 10)
1이상 10이하의 정수 난수 생성

## random.choice(fruits)
주어진 시퀀스 자료형에서 임의의 요소를 반환

## random.shuffle(squences)
주어진 시퀀스를 임의로 섞음

## random.sample(squences, 3)
리스트에서 중복되지 않게 3개 뽑기

## datetime 라이브러리
현재 날짜와 시간을 가져오기
```
import datetime

datetime.datetime.now()

#특정 날짜와 시간을 생성
date.datetime(...,...,.,.,.)

## 날짜와 시간형식 지정
datetime.datetime.now().strftime("...")

## 날짜와 시간 연산
now - datetime.timedelta(days=1)

시간대 변환
new_timezone = datetime.datetime.now().timezone('asia/seoul')
now.astimezone(new_timezone)
```


