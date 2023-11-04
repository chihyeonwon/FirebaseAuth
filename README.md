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
