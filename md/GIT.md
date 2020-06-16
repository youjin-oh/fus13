[README](../README.md)

# GIT 명령어

![git](../assets/git.png)

> 깃은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템이다. 소프트웨어 개발에서 소스 코드 관리에 주로 사용되지만 어떠한 집합의 파일의 변경사항을 지속적으로 추적하기 위해 사용될 수 있다.


git config --global user.name Youjin-Oh(깃아이디)

git config --global user.email oyj3474@naver.com  
  
git config --list  
  

echo "youjin" >> READ.md

cat READ.md

git remote -v

git status
git add md/CLI.md
git add .
git commit -m "이름추가(주석)"
git commit -m "이름추가(주석) -> enter -> 주석추가"
git push origin -u master

git log 로그 확인
git log -oneline

git tag : 버전에 tag 추가 또는 삭제하기
ex) git tag v3, git tag v2 a644db1

git reset : 버전 되돌리기
ex) git reset --hard v4

git tag -d : 버전 삭제
ex) git tag -d v1