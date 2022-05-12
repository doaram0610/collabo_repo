# 협업 테스트

- manager
  git init
  git add .
  git commit -m "first commit"
  git branch -M main //로컬 브랜치명 변경, 왜냐면 init 시에 자동으로 master 로 생성된 브랜치를 깃헙에 있는 브랜치명과 동일하게 바꿔줘야 한다. 버전업 되면서 불필요한 과정이 생긴거다.
  git remote add origin https://github.com/doaram0610/collabo_repo.git
  git push -u origin main

Github에 접속하면 화면에 노란박스로 푸시된거 확인하라고 한다.
compare & pull request 버튼을 클릭해서 내용확인하고 머지 해준다.
