---
title: 깃허브 블로그 만들기(hexo 이용)
date: 2022/12/21 10:00:00
categories:
- Git
tags:
- 
- Git
- GitHub
- GitHub blog
- blog
- hexo
---

# Git hub blog - hexo

**1. 필수 파일 설치**

- [nodejs.org](https://nodejs.org/en/download/) 다운로드
    - 설치 시 주의 사항
    
    ![Untitled](/images/2022/12/Git_hub_blog/Untitled.png)
    
    ![Untitled](/images/2022/12/Git_hub_blog/Untitled%201.png)
    
- git bash에서 확인

```bash
node -v
```

- hexo 설치

```bash
npm install -g hexo-cli
```

**2.  블로그 생성**

- 적당한 폴더 생성(차례대로 실행)

```bash
$ mkdir myblog
$ cd myblog
```

- 블로그 파일명 생성(차례대로 실행)

```bash
$ hexo init myblog
$ cd myblog
```

- <자신의 닉네임>.github.io 생성
    
    ![Untitled](/images/2022/12/Git_hub_blog/Untitled%202.png)
    
- npm 설치

```bash
$ npm install
$ npm install hexo-server --save
$ npm install hexo-deployer-git --save
```

- _config.yml 파일 설정
    - 사이트 정보 수정
    - 블로그 URL 정보 설정
        
        ![Untitled](/images/2022/12/Git_hub_blog/Untitled%203.png)
        
    - 깃허브 연동
    
    ![Untitled](/images/2022/12/Git_hub_blog/Untitled%204.png)
    

**3.  깃허브에 배포**

- 차례대로 실행 후 [http://localhost:4000/](http://localhost:4000/) 에서 접속 확인

```bash
$ hexo generate
$ hexo server
INFO  Validating config
INFO  Start processing
INFO  Hexo is running at http://localhost:4000/ . Press Ctrl+C to stop.
```

- 최종적으로 배포

```bash
$ hexo generate
$ hexo deploy
```

- 배포 완료 후 SeungKyu37.github.io에 접속해 확인