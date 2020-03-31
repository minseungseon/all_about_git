#실습 코드 정보)  

```
git --version  
git init  
git status  
git add . 또는 git add -A  
git commit -m "first commit of gitclass101"  
  
//무언가가 뜬다면 자신의 정보를 넣어줍니다.   
git config --global user.email"lisa71631999@naver.com"  
git config --global user.name "seonminseung"  
  
다시 commit 해주기  
  
git status 한번 더 해주기  
수정해보고 status 확인도 해주기  
git add .   
git commit -m "modified html file"  
  
이렇게 되면 지금까지 두번의 커밋을 하게 됨.   
  
이제 온라인으로 갑시다!   
git hub 들어가기 -> repository 만들기 ( 보통 이름은 gitclass101 )   
git hub에 있는 설명대로 하기!  
  
git remote add origin https://github.com/minseungseon/all_about_git.git  
git push -u origin master   
reject된다면 git push origin +master  
```
