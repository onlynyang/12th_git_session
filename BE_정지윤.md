# 12th_git_session
---
## 1주차 깃 세션 요약

- #### 깃 & 깃허브
    + 깃이란? 분산 버전 관리 시스템
    + 깃이 파일에 대한 기록을 작성하면, 깃허브가 사람들에게 공유할 수 있게 해주는 역할을 한다.
    + 깃 사용법(혼자)
        1. 개인 레포지토리 생성
        2. 로컬에서 폴더 생성 후, 사용자 등록
        3. 개인 레포지토리에 연결(origin)
        4. 폴더에서 파일 수정 및 편집
        5. 폴더에서 파일 수정사항 반영(add 및 commit)
        6. 폴더를 PUSH하여 개인 레포지토리에 반영

    + 깃 사용법(같이)
        1. 중앙 레포지토리 생성
        2. 중앙 레포지토리를 fork하여 개인 레포지토리 생성
        3. 폴더 생성 후, 중앙 레포지토리와 개인 레포지토리에 연결(origin과 upstream)
        4. Branch 생성
        5. **upstream에서 PULL**
        6. 폴더에서 파일 수정 및 편집
        7. 폴더에서 파일 수정사항 반영(add 및 commit)
        8. **upstream에서 PULL**
        9. 폴더를 PUSH하여 개인 레포지토리에 반영
        10. 개인 레포지토리에서 pull request 하기
        11. 중앙 레포지토리에서 코드 확인 후 merge 받기
        12. 폴더의 main브랜치에 수정사항 반영
        13. 이전 브랜치 삭제

---

- #### 프레임워크(Django)
    + 프레임워크란? 개발에서 반복적인 작업을 최소화하고 쉽고 빠르게 애플리케이션을 개발할 수 있도록 해주는 개발 도구
    + Django란? 파이썬으로 작성된 웹 애플리케이션 프레임워크     
    + Django 개발환경 세팅
        1. Django가 다른 프로젝트에 영향을 끼치지 않도록 독립적인 가상환경 설정
            설치하기: __pip3 install pipenv__
            켜기: __pipenv shell__ 
        2. Django 설치
            설치하기: __pip install django__
            프로젝트 파일 생성: __django-admin startproject (project name)__
        3. settings.py 초기설정하기
        4. App 생성
            앱 설치하기: __python manage.py startapp (app name)__
            settings.py에 설치한 앱 등록
        5. 서버 실행 (앱의 변경사항을 데이터 베이스에 적용하는 과정)
            migrate하기: __python manage.py migrate__
            서버 실행하기: __python manage.py runserver__
    + Project와 App 비교하기
        - Project: 환경설정과 앱의 집합. 프로젝트를 관리함. 여러 앱을 가질 수 있음.
        - App: 프로젝트를 구성하는 기능의 집합 단위.

