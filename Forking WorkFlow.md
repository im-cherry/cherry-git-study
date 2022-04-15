# Forking WorkFlow

깃허브로 협업하기 - Forking WorkFlow 방식의 협업

<br/>
<br/>

## 1. Forking WorkFlow 란?

- 프로젝트 참여자가 개인 로컬 저장소와 자신의 원격 저장소(중앙 원격 저장소를 fork한 것)를 가지고 협업을 진행하는 방식
- 각자 자신의 원격 저장소에 푸시하고 이 내용을 중앙 원격 저장소에 pull request 한 뒤, 프로젝트 owner가 다른 개발자의 기여분(PR)을 원격 저장소에 병합할지 안할지 결정

<br/>
<br/>

## 2. Forking WorkFlow 방식

① 중앙 원격 저장소를 Fork 해서 자신의 원격 저장소를 만든다.

<br/>

② 프로젝트 참여자는 자신의 원격 저장소를 로컬 저장소에 복제한다.
```bash
$ git clone [자신의 원격 저장소 URL]
```

<br/>

③ 프로젝트 중앙 원격 저장소를 연결한다. (일반적으로 자신의 원격저장소는 clone할때 origin으로 자동 연결된다.)

```bash
$ git remote add upstream [중앙 원격 저장소 URL]
```

<br/>

④ 자신이 구현할 기능 이름으로 브랜치를 하나 생성한 후, 프로젝트 작업을 진행한다.

```bash
$ git checkout -b [브랜치 이름]
```


<br/>

⑤ 기능 구현을 마친 후, 자신의 원격 저장소에 push 한다.

```bash
$ git add .
$ git commit -m "커밋 메세지"
$ git push origin [브랜치 이름]
```

<br/>

⑥ 나의 원격 저장소에서 구현한 기능의 브랜치를 선택해 프로젝트 owner에게 pull request를 던진다.

<br/>

⑦ 프로젝트 관리자는 변경 내용을 확인한 후 중앙 원격 코드 베이스에 merge 한다.

<br/>

⑧ 중앙 원격 저장소의 코드 베이스에 새로운 커밋이 있다면 로컬 저장소에 갱신한다.

```bash
git pull upstream [브랜치 이름]
```


<br/>
<br/>

## Reference

- https://andamiro25.tistory.com/193_



