# TIL Day 02
## git을 배우는 이유 1일차 간단요약
1. 왜배우는가?
    - 버전관리, 포트폴리오
    - 백업, 복구 , 협업
2. 사전지식
    - CLI
    - GUI
    - 이것에 관한 명령어 mkdir, cd , ls
### Git 프로젝트 생성시 먼저 해야할 것
1. README.md
2. .gitignore
    - [.gitignore 파일 만들어주는 사이트](https://www.toptal.com/developers/gitignore)
### Git 협업 로컬저장소에서 가져오기
1. git clone
 - git clone URL
 - 다른사람의 원격 저장소를 가져올 수 있음
    1. 폴더만들기
    2. 내용복사
    3. git init
    4. git remote add origin URL
    위의 4가지기능을 클론으로 한번에 다운로드 받는다고 생각
2. git pull
 - 변경사항 업데이트 개념생각
 - pull로 받아오기 
 - git pull origin master
 - 버전을 당기고 push는 밀어서 입력 넣어주고
   