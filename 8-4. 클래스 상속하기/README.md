# 클래스 상속하기
기존 클래스를 확장하고 재사용하는 방법
```
class 부모클래스:
class 자식클래스(부모클래스):
```
새로운 속성이나 메서드를 추가하거나 부모 클래스의 메서드를 재정의(overide)
필요한 경우 super() 함수를 사용하여 부모 클래스의 메서드를 명시적으로 호출할 수 있다.

부모클래스 먼저 만들기
def __init__(self, name, health, magic_power):
  super().__init__(name, health)

def attack(self):
  super.attack()
  ...





