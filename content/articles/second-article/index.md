---
title: "Git이랑 싸웠다."
description: "컴퓨터 바뀔 때 마다 속 썩이기 No.1"
date: "2022-12-09"
banner:
  src: "../../images/kelly-sikkema-Hl3LUdyKRic-unsplash.jpg"
  alt: "First Markdown Post"
  caption: 'Photo by <u><a href="https://unsplash.com/photos/Nc5Q_CEcY44">Florian Olivo</a></u>'
categories:
  - "잡담"

keywords:
  - "React"
  - "Gatsby"
  - "Markdown"
  - "Blog"
  - "Git"
---

## Git Config 

``` 
git config --global user.name "Doping7"
git config --global user.email mh271704@gmail.com

```




### 1. 발단
6월 쯤? 노트북을 샀었다. 그것도 갬성 잔뜩 충전해주는 MacBook으로 다가.  
이게 진짜 감성 좋고 다 좋은데 열 받는게 윈도우에 익숙해져 있으니 적응이 안된다. 
어쨌든 맥 사용에 열심히 적응해서 지금은 무난하게 잘 사용하고 있다.  
문제는 git을 사용하면서 발생했는데 이게 이전엔 내가 어떻게 했었는지도 기억이
안날 뿐더러 (git config를 막 개발하듯 계속 붙잡고 있을 일이 없다. )
  
사용하는 노트북이 바뀌니까 (심지어 윈도우에서 맥으로 대변화! 🙌)  
더 감당하기가 힘들다. git 깔겠다고 생각도 안했던 HomeBrew도 깔고..  
개발하는 것보다 세팅하는데 시간을 더 많이 투자하는 것 같다. 

어쨌든 중요한 문제는   
1. push가 안된다..?
2. 우여곡절끝에 github에 push를 하고보니 commit 내역에 내가 공부용으로 파둔 계정이
   author로 되어있다..?  

였다.


### 2. 해결 💡
뭐 별 짓을 다했다. 1번 문제점에서 엄청나게 시간을 빼앗겼는데  
난 애초에 github에 원래 push할땐 그냥 계정 이름 치고 비밀번호 치면 되었던걸로 기억했다.
근데 맥에서 푸시를 해보려니 짦은 메세지가 하나 뜨는데 내 짧은 영어로 보기에 
이젠 password 인증을 지원하지 않으니 토큰 발급해오라는 느낌? 이더라..  

그래서 repo에 관련한 권한을 모두 부여한 토큰을 발급받아서 그 토큰 값을 password자리에
입력해주니 어찌저찌 push가 가능해졌다. 

2번 문제점은 좀 오래 걸리지는 않았는데 어이가 없었다. 
로컬에 git을 처음 깔고 remote 저장소를 처음 추가하면 
계정 정보를 처음에 등록하게 되는데 이 정보가 계정 이름이랑 email이다.  

난 여기서 email을 공부용 계정의 email로 입력해서 공부용 계정의 이름이 떴던 것 같다.
email을 지금 사용중인 계정의 email로 변경해주니 에쁘게 다시 계정 이름이 돌아왔다.




