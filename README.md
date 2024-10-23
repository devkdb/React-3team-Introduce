# React-Introduce-3team

## 팀원들 소개 프로젝트입니다.

# 팀 프로젝트 규칙

## 팀 프로젝트용 원격 저장소 연결

1. 작업 폴더 만든다.
2. git clone https://github.com/devkdb/React-3team-Introduce.git
3. 현재 어떤 브랜치 상태인지 확인 (main에서 작업할것)
4. git pull origin main
5. git switch -c <main-자기이름>
   - 예) git switch -c main-김두봉
6. <main-자기이름> 브랜치에서 작업시작

## 원격저장소에 내가 만든 데이터 저장0. 현재 상태 확인

0.브랜치가 <main-자기이름> 상태인지 확인

1. 원격저장소 데이터 가져온다

   - .git pull origin <main-자기이름>
   - . 충돌나면 merge한다.

1. add, commit, push 한다.

- git add .
- git commit -m '자기소개 html 파일만들기'
- git push origin feature/김두봉\_소개

2. GitHub의 현재 브랜치에서 develop브랜치로 PR 날린다.

- 부탁받은 사람은 소스 검토후 approve 및 Merge.
