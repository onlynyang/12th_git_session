# 깃을 사용하는 이유는?
파일에 있어 수정사항은 계속 발생하기 때문에 번거로움이 발생할 수 있음
==> 깃을 사용하면 하나의 파일에 수정사항을 계속 반영해주기 때문에 편리함.

# <1> 깃사용법
1.	개인 레포지토리를 생성(README 파일 체크 잘 확인해주기)
2.	git config —global user.name (email)
3.	
깃을 사용하는 이유는?
파일에 있어 수정사항은 계속 발생하기 때문에 번거로움이 발생할 수 있음
==> 깃을 사용하면 하나의 파일에 수정사항을 계속 반영해주기 때문에 편리함.

# <1> 깃사용법
4.	개인 레포지토리를 생성(README 파일 체크 잘 확인해주기)
5.	git config —global user.name (email)
6.	연동: git init
7.	git remote add origin “복사한주소” => git remote => git branch -M main
8.	최신 사항 반영: git pull origin main
- 파일 수정 이후
9. git add
10. git commit -m “커밋 메시지”
11. git push origin main
커밋 끝!

# <Django>
1. vsc 오픈
2. 깃 연동 배웠던 내용을 바탕으로 하기!
3. 가상환경 설정하기
 - 설치: pip3 install pipenv
 - 켜기: pipenv shell
4. Django 설치하기
 - pop install django
5. 앱생성
6. 서버 실행(migrate!!!)
