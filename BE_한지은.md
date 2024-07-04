- 깃 사용법
- 1) 폴더 생성, code로 열기
  2) git init
     git remote add origin "개인 레포리지 주소"
     git remote add upstream "중앙 레포리지 주소"
     git remote -v : 연동 확인
     git branch -M main : 기본 브랜치 이름 master에서 main으로 변경
     git pull upstream main : 중앙에서 최신사항 불러오기
     git branch : branch 목록 확인
     git branch "새이름" : 새 브랜치 생성
     git add .
     git commit -m "커밋메시지"
     gut pull upstream main
     git push origin "현재 브랜치 이름"