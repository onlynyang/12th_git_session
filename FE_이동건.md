# 깃&깃허브 세션 요약
- ## 깃이란?
    깃(git)은 분산 버전관리 시스템으로 파일의 변경사항을 추적하고 여러 사용자들간의 파일에 관한 작업을 조율하는데 사용됨.
<br>
- ## 깃 사용법(혼자)
    1. github에서 레포지토리 생성 
    2. 로컬에서 폴더 생성, 사용자등록 /git config --global user.~ 
    3. 원격 저장소에 연결 /git remote add origin ~ 
    4. main branch의 최신사항 반영 /git pull origin main 
    5. 파일 수정 후 원격저장소에 반영 /git add/commit/push
    6. github에서 수정된 파일 확인 
<br>
- ## 프레임워크 Django 개발 환경 세팅
    1. 프로젝트들을 모아둘 Workspace 생성
    2. 작업할 폴더 생성후 git연동 /cd명령어를 통해 디렉토리 변경가능 
    3. 가상환경 설정하기 
        pip3 install pipenv명령어로 설치, pipenv shell 명령으로 가상환경 켜기
    4. Django 설치하기&프로젝트 파일 생성 
        파일 생성후 settings.py 초기설정하기
    5. App 생성 
    6. 서버실행
        앱 생성 후 migrate 하기 (데이터베이스에 적용하는 과정)
        runserver 명령으로 서버실행하기 
