# 람다
호출될 때 값이 구해지는 하나의 표현식. 또 이름이 없는 인라인 함수
lambda [parameters]:expression
파이썬에서 함수는 일급객체입니다.
variable = lambda [parameters]:expression
expression 부분은 변수 없이 식 한 줄로 표현 가능해야 함

## 람다feat. map()
print(list(map(lambda x, y : x * y, a, b)))

## 람다feat. filter()
list(filter(lambada x:x%3==0 and 0 < x < 10, a))



