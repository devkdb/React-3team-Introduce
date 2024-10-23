# React-Introduce-3team

## 팀원들 소개 프로젝트입니다.

# 팀 프로젝트 규칙

## 팀 프로젝트용 원격 저장소 연결

1. 작업 폴더 만든다.
2. git clone https://github.com/devkdb/React-3team-Introduce.git
3. 현재 어떤 브랜치 상태인지 확인 (main에서 작업할것)
4. git pull origin main
5. git checkout dev
6. git pull origin dev
7. git switch -c <dev-자기이름>
   - 예) git switch -c dev-김두봉
8. <dev-자기이름> 브랜치에서 작업시작
9. 한글로 자기소개 폴더를 만들어서 작업 한다.
10. 아래처럼 폴더 예정

```javascript
/index
/김두봉-소개/
/배진한-소개/
/최종훈-소개/
/김혁진-소개/
/박지흔-소개/
/임예지-소개/
```

## 원격저장소에 내가 만든 데이터 저장0. 현재 상태 확인

0.브랜치가 <dev-자기이름> 상태인지 확인

1. 원격저장소 데이터 가져온다

   - .git pull origin <dev-자기이름>
   - . 충돌나면 merge한다.

1. add, commit, push 한다.

- git add .
- git commit -m '자기소개 html 파일만들기'
- git push origin <dev-자기이름>

2. GitHub의 현재 브랜치에서 develop브랜치로 PR 날린다.
   <dev> <------ <dev-자기이름> 에서 dev로 PR요청

- 부탁받은 사람은 소스 검토후 approve 및 Merge.
