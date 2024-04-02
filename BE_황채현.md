<git 사용법>
 - git을 사용해야 하는 이유: 팀프로젝트를 할 때 각자의 수정사항을 바로바로 변경해줄 수 있음
   -> 수정사항이 있을 때마다 다른이름으로 저장하지 않고 git hub을 통해 수정 후 내용과 수정 전 내용 모두 쉽게 볼 수 있음 (microsoft web에서 하는 ppt 공동작업이랑 비슷한 듯..)

1. github에서 개인 레포 생성(레포 설명 ,readme파일 생성 여부, gitignore 파일 생성여부(중요한 코드 저장? -> 공유 안되도록...))
2. 내 컴퓨터에서 폴더 생성하고 vscode로 실행 -> 사용자 등록(git config --global user.name/email )
3. git의 나의 레포와 내 컴퓨터 연결(git init, git remote origin ______)
4. 레포에서 가져오기 (git remote origin main(master -> main으로 고쳐서 main 씀))
5. 수정하고 저장 후 코멘트 하고 레포로 보내기(git add .(add 뒤 띄어쓰기 중요) / git commit -m "수정한 내용"  / git push origin main)

<개발환경 setting>
pip install : 뭔가를 설정/설치하는 명령어?

<서버 실행>
앱 생성 후 migrate 꼭 해야함!!(python의 경우 : python manage.py migrate  /  python manage.py makemigrations)
서버 실행 : python manage.py runserver