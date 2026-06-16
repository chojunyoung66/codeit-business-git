#git : 버전관리 시스템(깃)
- 프로젝트 폴더를 버전별로 저장 할 수 있는 시스템

# 깃 사용자 설정
- git config --list
- git config --global user.name "xxxx"
- git config --global user.email "xxx@mail.com"

# 깃 사용 방법
1. 프로젝트 디렉토리를 깃으로 관리하기 시작한다.
- git init
  .git 폴더 생성 (숨김폴더)
2. 깃으로 관리하는 프로젝트 디렉토리는 아래의 3단계로 구분된다.
- 워킹 디렉토리
  - tracked : 스테이징 에어리어에 기록된 파일과 폴더
  - untracked : other
- 스테이징 에어리어(장바구니)
- 로컬 리포지토리(구매내역)

3. 현재 프로젝트 폴더의 상태를 파악
- git status

4. 현재 프로젝트 폴더 상태를 저장
- git add [스테이징에 추가하고 싶은 파일 또는 폴더햣 ]