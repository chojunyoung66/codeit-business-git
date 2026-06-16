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
- git add [스테이징에 추가하고 싶은 파일 또는 폴더 ]
- git add .
- git commit -m 메세지

5. 저장된 기록을 확인
- git log

6. 다른 저장 기록으로 이동
- checkout : HEAD를 이동
- git checkout [브랜치 이름]
  - HEAD 가 브랜치를 가리킨다
- git checkout [커밋아이디]
  - HEAD 가 특정 커밋을 가르킨다
  - HEAD 가 브랜치에서 이탈(detached)했다.