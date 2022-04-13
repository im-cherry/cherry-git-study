# cherry-git-study

### 1. git 이란?

컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템(DVCS)이다.

#### 1) VCS(Version Control System)

- 버전 관리 시스템
- 소프트웨어 개발 및 유지 보수 과정에서 발생하는 소스 코드, 문서 등의 생성/변경/삭제 등을 관리하는 시스템

#### 2) CVCS(Centralized Version Control System)

- 중앙 집중식 버전 관리 시스템
  ![image](https://user-images.githubusercontent.com/100753621/163216718-7e2b7dd9-9ca8-4bb9-a06e-1cbc5a3153c5.png)
  _그림출처 : https://heekangpark.github.io/git/vcs_

#### 3) DVCS(Distributed Version Control System)

- 분산식 버전 관리 시스템
  ![image](https://user-images.githubusercontent.com/100753621/163216807-08aa96c5-10b2-4f19-bd26-51f5952eb52f.png)
  _그림출처 : https://heekangpark.github.io/git/vcs_

### 2. git 설치

[git 공식 사이트](https://git-scm.com/downloads)에서 운영체제에 맞는 프로그램 설치하기

### 3. git 설정

```bash
$ git config --list  # 설정 확인
$ git config --global user.name "im-cherry"  # 사용자 이름 설정
$ git config --global user.email "collcr@kakao.com"  # 이메일 주소 설정
$ git config --global core.autocrlf ture  # 줄바꿈(\r\n → \n) 문자열 설정
```

### 4. git 초기화 및 삭제

```bash
$ git init     # git 초기화
$ rm -rf .git  # git 삭제
```

### 5. git command

![image](https://user-images.githubusercontent.com/100753621/163220583-aa82c032-e7f3-42f4-be7a-2ca860434e51.png)
_그림 출처 : https://wiki.sansae.net/display/PS/13-02.+Git+Case+Study_
