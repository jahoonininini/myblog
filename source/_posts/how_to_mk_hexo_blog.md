---
title: How to makes hexo blog
---

## 개요
- 간단하게 Hexo 블로그를 만들어 본다.

## 필수 파일 설치
- 1단계: nodejs.org 다운로드

```
$ node -v
```

- 2단계: git-scm.com 다운로드
```
$ git --version
```
- 3단계: hexo 설치
    - hexo는 npm을 통해서 설치가 가능하다.
```
$ npm install -g hexo-cli
```
## 블로그 만들기
```
$ hexo init myblog
$ cd myblog
$ npm install
$ npm install hexo-server --save
$ npm install hexo-deployer-git --save
```
## 깃허브에 배포하기
```
$ hexo generate
$ hexo server # localhost:4000 에서 접속을 확인
$ hexo deploy
```