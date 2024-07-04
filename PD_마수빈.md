12기 깃 세션

1. 깃&깃허브
    1) 깃: 수정사항을 반영한 파일을 계속해서 업데이트
    2) 깃허브: 깃의 수정사항 기록 (깃허브를 통해 수정사항 기록을 공유)

2. 개인 깃 사용법
    1) 깃허브에서 개인 레포지토리 생성 + 로컬 폴더 생성 후 개인 레포지토리에 연결
    2) VScode와 연동하기 - 로컬 폴더에서 파일 연동 
    3) 사용자 등록 (git config --global user.name '깃허브아이디' / git config --global user.email '깃허브이메일')
    4) 깃허브와 폴더 연결 (git init / git remote add origin '주소' / git remote -v / git branch -M main)
    5) 변경사항 저장 - 수시로 할것 (git pull origin main)
    6) 수정 후 업로드 (git add / git commit -m 'Edit 파일명' / git push origin main)

3. Django
    1) 폴더 생성 후 깃에 연동
    2) 가상환경 설정 
        - 설치: pip3 install pipenv
        - 켜기: pipenv shell
    3) Django 설치
        - 설치: pip install django
        - 프로젝트 파일 생성: django-admin startproject 'projectname'
    4) 초기 설정 (ALLOWED_HOSTS, LANGUAGE_CODE, TIME_ZONE, USE_I18N, USE_TZ)
    5) 앱 생성: python manage.py startapp 'app name'
    6) 서버 실행 (python manage.py migrate / python manage.py makemigrations / python manage.py runserver)