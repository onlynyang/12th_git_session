# 240327_동대멋사_깃세션_내용정리
- 깃 & 깃허브
    1. 깃이 뭔가요?
    깃은 분산 버전관리 시스템으로, 컴퓨터 파일의 변경사항을 추적하고 여러명의 사용자들 간에 파일에 대한 작업을 조율하는 데 사용되는 협업 및 데이터 저장 툴입니다.
    2. 깃 + 깃허브
    "깃은 파일에 대한 역사책을 쓴다. 그리고 출판사는 깃허브이다. (PUSH)
- 깃 사용법 (혼자)
    1. 레포지토리 생성
    2. 사용자 등록
        git config --global user.name @@
        git config --global user.email @@
    3. 생성한 원격저장소에 연결 
        git remote add origin @@  
    4. 최신사항을 반영한다
        git pull origin main
    5. 파일의 편집 및 추가 생성
        저장을 습관화하자
    6. add / commit / push
        git add . : 현재 작업중인 프로젝트의 모든 변경사항을 다음 커밋에 포함시키기 위해 준비하는 과정. '.'는 현재 디렉토리를 의미하고, 이는 모든 변경사항을 추가하겠다는 것을 뜻한다.
        git comit -m "파일명" : "파일명"은 역사책에 기록할 내용을 뜻한다.
        git push origin main : main branch에 지금까지의 모든 변경사항을 저장하겠다.
- Django 사용법
    1. Django?
        파이썬으로 작성된 웹 애플리케이션 프레임워크
        데이터베이스 모델링, URL 라우팅, 템플릿 처리, 사용자 인증, 관리자 패널 등의 기능을 내장
    2. Framework?
        웹 서비스를 만들어주는 기계
        소프트웨어 개발에서 반복적인 작업을 최소화하고 쉽고 빠르게 애플리케이션을 개발할 수 있도록 도와주는 개발 도구
    3. 가상환경 구성하기
         pip3 install pipenv
         pipenv shell
    4. Django 설치
        pip install django
    5. 프로젝트 및 앱 설치
        python manage.py startapp main
        main 앱 추가하기 (수동)
    6. 앱 생성 후 migrate
        python manage.py migrate
        python manage.py makemigrations
    7. 서버 실행하기
        python manage.py runserver
    **project vs app
    프로젝트 : 환경설정, 앱의 집합 / 여러개의 앱을 포함할 수 있음
    앱 : 프로젝트를 구성하는 기능의 집합단위
    ex) 프로젝트 : 인스타그램
        앱 : 게시글 / 회원정보
