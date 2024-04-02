# 12th_git_session_Summary


## git and github
- git : git이란 파일에 대한 역사책을 쓰는 것.
- git hub : git이 쓴 내용을 출판하는 출판사.

***
## 깃 사용법 혼자
    1. Github에서 개인 레포지토리 생성
    2. 로컬에서 폴더 생성 후, 사용자 등록 
    -> git config --global user.name//email 본인 깃허브 아이디 또는 이메일 
    3. 생성한 개인 레포지토리에 연결 -> git remote add origin 을 통해 연걸
    3.5 git pull origin main 을 통해 깃허브의 main branch 최신사항 반영
    ***
    (프로젝트 내내 반복!!)
    4. 폴더에서 파일 수정, 편집 
    5. 폴더에서 파일 수정 사항 반영 -> git add . // git commit -m "커밋메시지"
    6. 폴더를 PUSH하여 개일 레포지토리에 반영 -> git push origin main

## Django 개발 환경 세팅하기
    1. pin3 install pinpenv를 통해 가상환경 설치
    2. pip install django를 통해 장고를 설치하고 프로젝트 파일 생성 후 setting.py에서 초기설정하기
    3. python manage.py start app "앱이름"  을 통해 앱 설치 후 setting.py에 앱이름 등록
    4. 앱 생성 후 migrate는 필수!
    5. 서버 실행하기
