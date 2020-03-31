# git branch와 merge  
>git branch와 merge에 대한 ***cheating note*** 입니다!  
  
## git branch 만들기  
```
$git branch 가지이름  
```  

## git branch 확인하기
```
$git branch  
```
  
## git branch 바꿔타기
```
$git checkout 가지이름
```
## branch파고 commit 후 merge까지 
```
$git branch branchex  
$git checkout branchex  
$git add .  
$git commit -m "branch test"  
$git push origin branchex  
$git checkout master  
$git merge branchex  
$git push origin master  
```

