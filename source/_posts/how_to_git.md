---
title: how_to_github, git
---
AI 수업에서 처음배운 git 사용 방법과 github 와의 연동 그리고 기타 명령어에 대해서 정리한다.

## git

### git 설치

https://git-scm.com/downloads 에서 git 을 먼저 설치한다.

### github

github 에서 새로운 저장소를 만들어 준다.

### git

git Bash 를 실행해준다.
``` bash
$ git init
$ git clone + 저장소 경로
```

### 계정 로그인
``` bash
$ git config --global user.name "name"
$ git config --global user.email "email"
```

### git 을 통해 github 에 커밋
``` bash
git add .
git commit -m "커밋 메시지"
git push
```