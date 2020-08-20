# Git

git 명령어 정리

#### git init

```git
git init
```

git 초기화

#### git add

```git
git add <폴더이름> # 폴더 추가
git add add . # 모든 폴더 추가
git add <폴더>/<파일> <폴더>/<파일> # 각각 파일 하나씩 추가
```

git에 폴더 추가

#### git commit

```git
git commit -m "주석"
```

추가한 git을 commit해줘

#### git status

```git
git status
```

commit한 git 잘 올라갔나 현재 상태 확인

#### git remote

```git
git remote add origin <git 주소>
git remote -v # 연결된 git 확인
```

github랑 remote로 연결

#### git remove

```git
git remote remove origin
```

연결된 origin이라는 remote를 삭제

