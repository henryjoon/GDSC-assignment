# MTV 패턴!

# 장고 시작하기 위해서.
1. 폴더를 만든다.
2. VS CODE에서 오픈한다.
3. new terminal을 연다.
4. window일 때는 powershell이 아닌 command로 바꿔줘야 하지만 나는 맥북이다.
5. 가상환경을 생성한다. 이를 실행하는 명령어는 ''python3 -m venv venv'' 이다.
    *가상환경이 무엇인가?
     파이썬에서 독립적인 프로젝트를 위한 개별적인 공간이다.
     프로젝트를 여러개 진행할 때 라이브러리 구분하여 관리할 수 있게 해준다.
     다른 버전의 파이썬 라이브러리를 사용할 수 있게 해주기도 한다!
6. 가상환경을 생성한다. 이를 실행하는 명령어는 venv/bin 폴더에 들어가 source activate 입력한다.
7. pip3 install django를 누르고 장고를 설치한다.
8. 장고 프로젝트를 실행한다. 폴더까지 나와서 mkdir project 치고 cd project 치고 django-admin startproject config 친다
9. 이때 웹브라우저에서 127.0.0.1:8000 입력했을 때 서버 실행 여부를 확인할 수 있다.
10. settings.py 파일에서 언어와 시간을 우리나라에 맞게 변경한다. 이러면 서버 실행했을 때 한국어로 나온다.
-끄읕-