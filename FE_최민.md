# 0327 Git, Github
- Git : 하나의 파일에 수정사항을 계속 반영해주는 프로그램
- Github : 자신의 프로젝트를 업로드하고 다른 사용자와 협업하는 플랫폼

# Git 명령어 정리
- git init : 해당 폴더와 깃허브 연동
- git remote add origin "주소" : 복사한 주소를 연동
- git remote -v : 연동 확인
- git branch -M main : 기본 브랜치 이름을 main으로 변경
- git pull origin main : 깃허브의 main 브랜치의 최신사항 반영
- git add . : .은 해당경로 내의 모든 파일
- git commit -m "커밋 메시지" : 깃허브에 기록할 커밋 메시지 작성
- git push origin main : origin의 main 브랜치에 수정, 작성사항을 반영

# Git Branch 명령어 정리
- git branch : 브랜치 목록 확인
- git branch "이름" : 새 브랜치 생성
- git switch "이름" : 브랜치 이동
- git branch -d "이름" : 브랜치 삭제

# Framework와 Django - 웹 서비스를 만들어 주는 기계
- 가상환경 설치 : pip3 install pipenv
- 가상환경 켜기 : pipenv shell
- Django 설치 : pip install django
- 프로젝트 파일 생성 : django-admin startproject [프로젝트 이름]
- 앱 설치 : python manage.py startapp [앱 이름]
- migrate 하기 : python manage.py migrate,  python manage.py makemigrations
- 서버 실행 : python manage.py runserver