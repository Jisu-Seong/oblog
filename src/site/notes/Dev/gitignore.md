---
{"dg-publish":true,"permalink":"/dev/gitignore/","dgPassFrontmatter":true,"noteIcon":"","created":"2024-08-18T15:02:00.606+09:00","updated":"2024-08-18T15:02:50.212+09:00"}
---

github에 올라가지 않을 파일을 적어두는 곳.

백과 프론트를 같이 업로드해도 각각 2개가 있어도 상관없음

gitignore 적용이 안될 때 - [[Dev/git\|git]] 캐시 삭제 방법
```
git rm -r --cached . 
git add . 
git commit -m "removed cached" 
git push -u origin main
```

"#"이 주석임
