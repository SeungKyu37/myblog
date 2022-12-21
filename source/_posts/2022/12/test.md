---
title: 자바 설치 방법
date: 2022/12/19 14:04:25 
categories:
- Git
tags:
- Git
- Github
---

# Git & Github 설정

## 다운로드

- Git : [https://git-scm.com/downloads](https://git-scm.com/downloads)

![Untitled](/images/2022/12/test/Untitled.png)

![Untitled](/images/2022/12/test/Untitled%201.png)

visual studio code 설치 후 

![Untitled](/images/2022/12/test/Untitled%202.png)

Repositories에서 프로젝트 생성

![Untitled](/images/2022/12/test/Untitled%203.png)

코드 링크 복사 후

![Untitled](/images/2022/12/test/Untitled%204.png)

바탕 화면 마우스 우 클릭 Git Bash Here 클릭

git clone Shift+”insert” 입력

바탕 화면에 생성된 프로젝트 우 클릭 후 Git Bash Here 클릭

code . 입력

![Untitled](/images/2022/12/test/Untitled%205.png)

.gitignore에 [gitignore.io](http://gitignore.io)에서 가져온 내용 뒷 부분에 복사

![Untitled](/images/2022/12/test/Untitled%206.png)

New Terminal 클릭

![Untitled](/images/2022/12/test/Untitled%207.png)

git bash 추가

![Untitled](/images/2022/12/test/Untitled%208.png)

TERMINAL에 

$ git commit -m "updated” 입력

에러 확인 후 

git config --global user.email "[xmcmrb@naver.com](mailto:xmcmrb@naver.com)" 입력

git config --global [user.name](http://user.name/) "SeungKyu37" 입력

git push 입력 후 엔터(defalut)

![Untitled](/images/2022/12/test/Untitled%209.png)

사이트([Authorize application](https://github.com/login/oauth/authorize?response_type=code&client_id=0120e057bd645470c1ed&state=c2eed072aca1421ba0cbe3543e106698&code_challenge_method=S256&code_challenge=RZaHGv0Vfi0pYT9EesfPm7zjC7JDlSiztKRdStMvMJQ&redirect_uri=http%3a%2f%2flocalhost%3a50179%2f&scope=repo+gist+workflow)) 뜨면 확인 누르고 연동 확인

git add . 입력

git commit -*m “your_*msg” 입력

git push 입력

으로 github에 프로젝트 갱신

![Untitled](/images/2022/12/test/Untitled%2010.png)