$ git branch
  main
* master


## 브랜치 생성
~ (master)$ git switch -c feature/01
Switched to a new branch 'feature/01'
~ (feature/01)$ 

## 브랜치로 전환
~ (feature/01)$ git switch master
M	README.md
Switched to branch 'master'

## 브랜치 삭제
~ (master)$ git branch -d feature/01
Deleted branch feature/01 (was 56d37b2).
