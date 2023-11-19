# Git 개요
Git 이란 분산 버전 관리 프로그램

Github 란 Git으로 관리하는 프로젝트를 저장하는 공간을 마련해주는 서비스


# Git 기본 기능
- Git init 파일명 : 현재 폴더를 Git으로 관리하겠다.

- Git add 파일명 : 어떤 파일을 작업이력으로 기록할 준비 (git add -all : 전체 add)

- Git commit -m"파일명" : add된 파일들을 바탕으로 새로운 변경사항(작업)을 기록

- Git status :  작업 상태 확인

- Git log : 작업 이력 확인 / Git log --oneline : 한줄로 확인 가능

- .gitignore: .gitignore에 포함된 파일은 Git에 추가되지 않는다.



# Git 되돌리기
- Git restore 파일명: 현재 버전으로 되돌리기(마지막 commit으로 된 상태로 되돌림)

- Git restore --staged 파일명 : add한거를 add 전에 걸로 되돌림.

- Git reset : commit 되돌리기 (자주 사용하지 말기)

# Git & Github
- Github의 프로젝트 컴퓨터로 가져오기 : Git clone <Git 주소>

- 컴퓨터의 프로젝트 Github에 올리기 : git remote add origin <Git 주소>, git push --set-upstream origin master

- Git push : 원격 저장소에 commit 업로드

- Git pull : Github의 새로운 이력을 컴퓨터로 가져오기

- conflict가 발생할때 
    1. 충돌이 발생한 파일을 수정해준다. (내용은 각각의 변경 이유를 살피고 직접 작성해야 한다.)
    2. git add 와 git commit을 이용해 새로운 commit을 생성
    3. conflict를 해소하는 새로운 commit을, 모두 공유하기 위해 push.
    4. 최종적으로 Github에 해당 내용이 반영되었음을 확인한다.

              
