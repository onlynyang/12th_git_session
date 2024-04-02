1. Git(개인)
# git repository 생성
# 로컬에서 폴더 생성후, 사용자 등록
- git config --global user.name 깃허브 아이디
- git config --global user.email 깃허브 이메일
# 연결
- git init
- git remote add origin "주소"
- git remote -v (확인)
- git branch -M main
- git pull origin main (중요)
# 파일 수정, 편집
# 수정 사항 반영
- git add .
- git commit -m "커밋메시지"
- git push origin main

2. Git(팀)
# 중앙 레포지토리에서 fork하여 개인 레포지토리 생성
# 폴더 생성 후, 중앙 레포지토리와 개인 레포지토리 연결
- git init
- git remote add origin "개인 레포지토리 주소"
- git remote add upstream "복사한 중앙 레포지토리 주소"
- git remote -v
- git branch -M main
# Branch 생성(그 전에 pull 하는 것 중요)
- git pull upstream main
- git branch
- git branch "브랜치 이름"
- git switch "브랜치 이름"(브랜치 이동)
- git branch -d "브랜치 이름"(브랜치 삭제)
# 폴더에서 파일 수정, 편집
# 수정 사항 반영
- git add .
- git commit -m "커밋메시지"
- git push upstream main
- git push origin "현재 브랜치 이름"
# 개인 레포지토리에서 pull request 하기
# 중앙 레포지토리에서 코드 확인 후 merge
# 폴더의 main 브랜치에 최신사항 반영
- git switch main
- git pull upstream main
# 예전 브랜치 삭제
- git branch -d "내 브랜치 이름"

3. Django 개발 환경 세팅
# 폴더 생성
# Git repository 생성
# Git 연동
# 가상환경 설정
- pip3 install pipenv(설치)
- pipenv shell(켜기)
# Django 설치
- pip install django
- django-admin startproject "project name"
# settings.py 초기 설정 (ppt 참고)
# app 생성
- python manage.py startapp "app name"
- setting.py에 설치한 앱 등록
# 서버 실행
- python manage.py migrate
- python manage.py makemigrations
- python manage.py runserver