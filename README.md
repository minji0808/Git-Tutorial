## 👋 Hi, I’m Minji Kim.
🏫 Soongsil Univ.
## 👀 I’m recently interested in ...
Playing the kalimba 🎵
## 🌱 I’m currently learning ...
Language : C, Python
```py
print("hello!")
```
___
# 강의 내용 정리
> **git과 github**
- git: 같은 파일에 대한 다른 버전을 보관할 수 있도록 하고 변경을 관리하는 도구
- github: 클라우드에 있는 git 제공자
- [개념 설명 영상](https://youtu.be/YFNQwo7iTNc)
> **git 저장소**
* 로컬 저장소, 원격(remote) 저장소로 나뉨
* local 저장소에서 작업한 것은 remote 저장소로 push 해줘야 변경사항이 git hub 서버에 반영됨

> **git의 기본적인 동작 과정**

![git의 기본적인 동작 과정](https://media.vlpt.us/images/hdy20201004/post/81366309-3edf-4f7c-97a9-4dd3deaa7883/%EA%B9%83%EC%9D%98%20%EB%8F%99%EC%9E%91%20%EC%9B%90%EB%A6%AC.png)

|git 프로젝트 구성요소|설명|
|:--:|--|
|working directory|작업할 파일이 존재하는 디렉터리|
|staging directory|commit을 수행할 파일이 올라가는 영역|
|git directory|git 프로젝트의 메타 데이터와 데이터 정보가 저장되는 디렉터리|

> **브랜치 사용하기**
- git branch 명령어 사용

> **충돌(conflict)과 병합(merge)**

## 새로 알게 된 내용/ 중요하다고 생각하는 내용
- git의 장점
  - 분산적인 개발, 효율적인 개발, 비선형적인 개발, 변경 이력 보장 
- git commit만 하고 이후 git push를 하지 않으면 github에 나타나지 않는다.
- git commit을 하면 자신의 컴퓨터 자체인 local repository에서만 기록이 되고 remote repository에는 반영이 되지 않기 때문
- 브랜치
  - 동시에 여러 개발자들이 프로젝트에서 각기 다른 기능을 개발할 수 있도록 branch 기능 제공
  - 기본적으로 마스터 브랜치가 자동으로 생성됨
  - 별도의 브랜치를 만들 경우 checkout 명령어 이용
  
