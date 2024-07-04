# 24.03.27 깃 세션 내용 정리
- 깃 사용하기
    1. github에서 레포지토리 생성
    2. 로컬에서 폴더 생성, 사용자 등록
        git config --global user.name @@
        git config --global user.email @@
    3. git init : 폴더와 깃허브 연결
        git remote -v : 연동 확인
    4. git pull origin main : 깃허브 main branch의 최신사항을 반영합니다
    5.파일 수정
    6.파일 저장하기
        git add . :  파일 내의 모든 변경 사항을 반영하기 위한 준비 단계
        git commit -m "커밋 메세지" : 깃허브에 기록할 내용을 저장합니다
        git push origin main : 지금까지의 변동사항을 모두 기록합니다.
-Django
    1. Django?
        파이썬으로 작성된 웹 애플리케이션 프레임워크
        프레임워크 : 웹 서비스를 만들어주는 기계
    2. 가상환경 설정하기
        pip3 install pipenv
        pipenv shell
    3. django 설치
        pip install django
    4. 프로젝트 파일 생성과 초기 설정
    5. App 생성
        phton manage.py startapp main
        main 이름의 앱을 수동으로 추가해야 함
    6. migrate 하기
        python manage.py migrate
        python mange.py makemigrations
    7. 서버 실행하기
        python mange.py runserver