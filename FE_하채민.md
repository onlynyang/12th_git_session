# 12th_git_session
12기 깃 세션



- 깃허브는 공동서류작업에 꼭 필요한 앱이다.
- 수정과 수정된 내용 공유가 편리하고 그 과정을 확인할 수 있다는 점이 최대 장점인 것 같다. 
 깃 사용법 (같이)

 1. 중앙 레포지토리를 fork하여 개인 레포지토리 생성

 2. git init / git remote add origin "개인 레포지토리 주소" / git remote add upstream "중앙 레포지토리 주소" / git remote -v(연동 잘 되었는지 확인절차)/git branch -M main(기본 브랜치 master 에서 main으로 변경)

 3. git pull upstream main (중앙 레포지토리에서 최신사항 불러옴)/ git branch (branch 목록 확인)/ 
 
 ---파일 수정 -------

 4. git add . / git commit -m "메세지"/git pull upstream main / git push origin "현재 브랜치 이름"(개인 레포지토리 반영)