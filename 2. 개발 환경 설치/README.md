# 개발환경 설정하기
## 자신의 컴퓨터 확인하기
윈도우키 + pause/brea키
32비트인지 64비트인지 확인
## 기본 설정
윈도우 탐색기 설정
- 숨김 파일, 폴더 및 드라이브 표시
- 알려진 파일 형식의 파일 확장명 숨기기 체크 해제
## 아나콘다 다운로드
<https://www.anaconda.com/>
용량이 큰데 파이썬이 큰게 아니라 라이브러리가 좀 사이즈가 크다
## 아나콘다 설치
(64bit 확인)
## 아나콘다 설치 확인
Anaconda Prompt 실행
## conda list
Anaconda와 같이 설치된 라이브러리 확인
## 여러 라이브러리들이 있음
## jupyter lab 실행 명령어 입력
서버를 동작시킨 것
크롬으로 접근 가능:<http://localhost:8888/lab>
파이썬을 작성할수 있는 환경을 GUI로 제공
## jupyter lab 종료 : Ctrl + C
## jupyter 설정 파일 만들기
jupyter notebook--generate-config 명령어를 입력하고 생성된 설정 파일의 경로를 확인
## 앞으로 소스 코드를 모을 Python 폴더 생성하기
C://Python
## 설정 파일에서 Ctrl+f를 누르고 'notebook_idr' 검색 경로 붙여넣기
앞에 샵이 있으면 주석이 됨
## 다시 jupyter lab 실행
## 커널 선택하기
## 01python.ipynb으로 파일명 변경 후 파이썬 버전 확인하기
```python
import sys
print(sys.version)
```
ctrl+enter(커서이동 X)
shift+enter(커서이동)
## !dir 명령어로 현재경로 확인하기
```python
!dir
```








