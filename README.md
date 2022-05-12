# 협업 테스트

## manager

### 최초작업

- git init
- git add .
- git commit -m "first commit"
- git branch -M main //로컬 브랜치명 변경, 버전업 되면서 불필요한 과정이 생긴거다.
- git remote add origin https://github.com/doaram0610/collabo_repo.git
- git push -u origin main
- Github에 접속하면 화면에 노란박스로 푸시된거 확인하라고 한다.(collabo 설정하면)
- compare & pull request 버튼을 클릭해서 내용확인하고 머지 해준다.

### 두번째부터

- git add .
- git commit -m "second commit"
- git pull origin main //내가 작업한거랑 자동 병합된다.
- git push origin main //collabo 설정하면 main 은 push 를 막는다.

## emp1

- 사원1은 clone 을 처음으로 수행
- 마지막의 명칭은 로컬에 생성되는 폴더명
- git clone https://github.com/doaram0610/collabo_repo.git collabo-repo-emp1

### 첫번째 작업

- git add .
- git status
- git commit -m 'commit1 emp1'
- git checkout -b emp1
- git branch
- git push origin emp1

### 두번째 작업

- git pull origin main //항상 main 에서 최신소스를 당겨오자
- git add .
- git status
- git commit -m 'commit2 emp1'
- git branch //현재 내 브랜치 확인한다. 머지하면 브랜치 삭제되서 생성해야 되기도 한다.
- git push origin emp1
