---
{"_filters":null,"_contexts":null,"_links":null,"_sort":{"field":"rank","asc":false,"group":false},"dg-publish":true,"permalink":"/dev/git/","dgPassFrontmatter":true,"noteIcon":"","created":"2024-08-18T12:14:04.521+09:00","updated":"2024-08-18T15:06:16.145+09:00"}
---

git bash

---
# 명령어 모음

### 최초 업로드 시 
- github에 있는거 그대로 베껴서 적으면 됨.

예시)
```
echo "# mymall_back" >> README.md 
git init 
git add README.md 
git add . 
git commit -m "first upload" 
git remote add origin https://github.git rcom/Jisu-Seong/mymall_back.git 
git branch -M main 
git push -u origin main
```

### 일반 커밋
- pull 받으려면 받고 하기

```
git add . 
git commit -m "커밋메시지" 
git pull 
git push -u origin main
```

### 연결 끊기
```
git remote remove origin
```

### branch 생성
```
git branch 브랜치이름

git switch 브랜치이름


// branch 합치기
git switch main

git merge 브랜치이름
```

### github거 내려받기
```
git clone 클론할_원격_저장소_주소
```