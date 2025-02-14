# 모듈
파이썬 코드를 담고 있는 파일로, 함수, 클래스, 변수 등으 ㄹ정의
재사용 되거나 불러와서 사용할 수 있는 독립적인 단위
## 모듈의 장점
코드의 구조화, 재사용성, 유지 보수성, 네임스페이스 관리
## 모듈 만들기
1. 새 노트북 만들기
2. 코드 작성
3. 모듈 저장
4. 모듈 파일로 변환
```
%%writefile character.py # 셀내용을 파이썬 모듈로 저장
class Character:
  def __init__(self, name, health)
    self.name = name
    self.health = health

  def attack(self):
    print(f"{self.name}이(가) 공격합니다.!")
```
## 모듈 불러오기
import문
1. 단일 모듈 불러오기
```
import math
```
모듈을 저장할 때는 변수 명명 규칙과 동일하게 숫자가 앞에 와서는 안 된다.
2. 모듈에 별칭 지정하기
import numpy as np
3. 특정 함수 또는 변수만 불러오기
from math import sqrt, pi
4. 모듈의 모든 요소 불러오기
from math import *
충돌 주의






