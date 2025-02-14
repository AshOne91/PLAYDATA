# 객체와 클래스
## 클래스
객체를 만들기 위한 주형
클래스 정의는 보통 클래스의 인스턴스를 대상으로 연산하는 메서드 정의를 포함
```
class ClassName:
  def method_name(self):
    method_body

  class_body
```

int, list, dict등도 클래스

## 객체? 인스턴스?
인스턴스는 특정 클래스로부터 만들어진 실체
ex) 리스트 클래스로 만들어진 인스턴스

instance_variable = ClassName()

## 메서드
클래스 바디 안에서 정의되는 함수
첫번째 인자로 인스턴스 객체를 받음
첫 번째 인자를 'self'라고 씀

## 클래스 속성
클래스 속성을 만들 때는 __int__ 메서드 안에서 self.속성에 값을 할당하면 됨
```
class Person:
  def __init__(self): # 생성자르 ㄹ나타냄 인스턴스가 생성되 때 최초 한 번 실행
    self.hello = "안녕하세요."

  def greeting(self):
    print(self.hello)

james = Person()
james.greeting()
```
