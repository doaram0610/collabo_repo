# 협업 테스트

## manager

### 최초작업

- git init
- git add .
- git commit -m "first commit"
- git branch -M main //로컬 브랜치명 변경, 왜냐면 init 시에 자동으로 master 로 생성된 브랜치를 깃헙에 있는 브랜치명과 동일하게 바꿔줘야 한다 버전업 되면서 불필요한 과정이 생긴거다.
- git remote add origin https://github.com/doaram0610/collabo_repo.git
- git push -u origin main

- Github에 접속하면 화면에 노란박스로 푸시된거 확인하라고 한다.
- compare & pull request 버튼을 클릭해서 내용확인하고 머지 해준다.

### 두번째 작업

- git add .
- git commit -m "second commit"
- git pull origin main
- git push origin main
- 이렇게 하면 되겠지?

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

- git pull origin main
- git add .
- git status
- git commit -m 'commit2 emp1'
- git checkout -b emp1
- git push origin emp1

### 세번째 작업

- 과연 될까?
- 무조건 pull -> checkout 하자
- 한번 삭제된 브랜치 다시 생성하면?
