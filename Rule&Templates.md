# Rule
* 어떤 규칙이
* 있을까나   

# Templates
## 📌branch
* 어쩌구
* 저쩌구   

## ✔️commit
* 어쩌구
* 저쩌구   

## ❗PR
* 어쩌구
* 저쩌구       

# Bash Code
## 🔁 local-git
```
cd "작업 경로"  # 로컬 폴더로 이동
git init  # 로컬 폴더 초기화
git remote add origin https://github.com/mynx6y/MS-DT-SCHOOL-1st-project.git  # 깃과 로컬 연결
git fetch origin 데2팀-"본인이름"  # 본인 브랜치만 내려받기
git checkout -b 데2팀-"본인이름" origin/데2팀-"본인이름"  # 브랜치 체크아웃 (로컬 브랜치 생성)
```   
### ✅ check
```
git remote -v
# 출력 예시
## origin https://github.com/mynx6y/MS-DT-SCHOOL-1st-project.git (fetch)
## origin https://github.com/mynx6y/MS-DT-SCHOOL-1st-project.git (push)

git status
# 출력 예시
## On branch 데2팀-"본인이름"
## Your branch is up to date with 'origin/데2팀-"본인이름"'.
```
## 🗂️ file upload/download
### ⬇️ pull
```
# 작업 전 원격 최신 내용 내려 받기
# 현재 내 로컬과 원격 내용이 일치하지 않으면, push 되지 않음

git pull origin 데2팀-"본인이름"
```   

### ⬆️ push
```
# 작업 후 원격에 로컬 내용 올리기
# git add . 은 모든 내용을 push 하게 됨
# 특정 파일만 push하려면 git add 파일1.txt 파일2.csv 등의 형식으로 작성

git add .
git commit -m "내가 수정한 내용(commit_templates.txt 참고)"
git push origin 데2팀-"본인이름"
```
