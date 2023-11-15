# FirebaseAuth
FirebaseAuth 개발 경험 정리
## 로그인 한 사용자의 가입일 출력
![image](https://github.com/chihyunwon/FirebaseAuth/assets/58906858/5a8ded0d-82c3-48c6-8c4d-79db46008fd2)     
![image](https://github.com/chihyunwon/FirebaseAuth/assets/58906858/deac18fb-aae3-4e69-8709-ede72676a88c)     
```
로그인 계정 관리 페이지에서 로그인한 사용자의 이메일 출력과 가입일을 출력해보았다.
firebaseAuth 객체의 metadata 메타데이터 정보 중에 creationTime을 utc 형식으로 보여주는 메서드가 있었고
이 데이터의 포맷형식을 SimpleDateFormat 메서드를 사용하여 한국의 날짜 형식으로 수정하였고 이를 xml에 넘겨주었다.
```
## FirebaseAuth 이메일인증

## FirebaseAuth 친구추가 기능
![image](https://github.com/mr-won/FirebaseAuth/assets/58906858/138cfbf5-190c-43a4-bf8e-524e2b498b70)     
![image](https://github.com/mr-won/FirebaseAuth/assets/58906858/92a4af20-b9cf-456b-a857-2733f92d186d)    
```
회원가입을 할 때 회원가입에 성공한 email을 user 데이터베이스에 넣었다.
user 데이터베이스의 데이터를 받아올 때 친구추가 리스트에 넣은 텍스트와 비교해서 그 텍스트를 포함한 데이터라면
userList에 추가하도록 해서 친구추가할 유저를 검색하는 기능을 개발하였다.
```

## FirebaseAuth 친구 리스트 기능
