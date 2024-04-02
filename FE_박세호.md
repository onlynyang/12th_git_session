## Git

> 깃은 2005년 리누스 토르발스에 의해 개발된 분산 버전관리 시스템이다.

## Github

> Github란 Git 파일들을 원격으로 저장하는 공간을 제공하는 서비스다. Github은 Git을 통해 프로젝트를 할 때 이 프로젝트를 저장하는 네트워크상의 저장 공간이다.

## Git 명령어

- git status
  - 현재 상태 확인
- git init
  - git 저장소 생성
- git add <파일명>
  - 커밋에 단일 파일의 변경 사항을 포함
- git commit -m "메시지"
  - 커밋 생성
- git push origin "branch"
  - 변경 사항 원격 서버 전송
- git pull
  - 원격에 저장된 git 프로젝트의 현재 상태를 다운받고 현재 브랜치로 병합
- git clone <https:.. URL>
  - 기존 소스 코드 다운로드 및 복제
- git branch
  - 브랜치 목록 확인

## 협업하기

    1. Github에 레포지토리 생성.
    2. 중앙 레포지토리를 fork하여 개인 레포지토리 생성.
    3. 디렉토리 생성 후, 중앙 레포지토리와 개인레포지토리에 연결.
    4. branch 생성 및 파일 수정 편집.
    5. upstream(중앙 레포)에서 pull하기!
    6. 파일 수정 사항 add, commit으로 반영.
    7. 개인 레포지토리에 push하여 반영.
    8. 개인 레포에서 PR하기.
    9. 중앙 레포에서 코드 확인 후, merge 받기.
    10. 디렉토리 main branch에서 수정사항 반영.
