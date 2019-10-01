# Quiz

## 깃폴더 생성
```
git clone https://github.com/rkdogo08/Quiz.git
cd Quiz
git init
git remote add origin https://github.com/rkdogo08/Quiz.git
```

## 깃 파일 수정&생성
```
git status
```
수정한 파일 모두추가
```

git add .
```
커밋 추가
```
git commit -m "add example"
git push
```

## 브랜치
브랜치 확인
```
git branch
```
solution 브랜치 생성
```
git branch solution
```
현재 브랜치 이동
```
git checkout solution
```

solution 브랜치 삭제
```
git branch -d solution

```
remote solution branch 생성
```
git push origin solution
```
remote solution branch 삭제
```
git push origin --delete solution
```
