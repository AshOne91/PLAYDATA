# 리스트 컴프리헨션
대괄호 안에 표현식과 fo문을 작성하여 사용할 수 있음

1. 이터레이터부터 값 꺼냄
2. 요소를 담은 변수를 활용하여 표현식을 실행
3. 표현식 결과 값을 리스트 요소에 넣음
4. 반복가능한 객체로부터 값이 없을때까지 1~3반복

```
list_c = [i for i in range(1, 10)]
print(list_c)
```

list_variable = [expression for 변수 in iterable]

list_variable = list(expression for 변수 in iterable)

[expression for 변수 in iterable if 조건식]
```
list_var2 = [i**2 for i in range(10) if i % 2 == 0]
print(list_var2)
[0, 4, 16, 36, 64]
```

```
[expresion for 변수 in iterable
            for 변수 in iterable
            for 변수 in iterable]

```
