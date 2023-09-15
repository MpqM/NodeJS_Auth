# Auth
#### ⚪ About Project
* ##### NodeJS로 jwt, 쿠키 세션, Oauth를 이용해 인증기능 구현
* ##### 간단한 jwt 엑세스토큰, 리프레시토큰 사용 인증 구현, 프론트엔드는 없음, postman collection 참고
* ##### 쿠키 세션과 PassPort(Strategy, Session Serializer, deSerializer)를 사용한 인증 구현
* ##### OAuth2.0을 활용한 구글, 카카오 로그인 인증, MongoDB를 이용해 사용자 모델을 정의하고 Oauth과 쿠키세션관련 사용자 정보 저장

* * *
#### ⚪ Usage
https://www.youtube.com/watch?v=vQkZ0dgmi9I
![image](https://user-images.githubusercontent.com/79093184/268300607-ec6350cc-e75c-4796-b58d-3ce3a4182c51.png)
* * *
#### ⚪ Built With
* ##### template engine
<img src ="https://img.shields.io/badge/ejs-F7DF1E.svg?&style=for-the-badge&logo=ejs&logoColor=white"/>

* ##### backend
<img src ="https://img.shields.io/badge/javascript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=white"/> <img alt="express" src ="https://img.shields.io/badge/express-339933.svg?&style=for-the-badge&logo=express&logoColor=white"/> <img alt="nodedotjs" src ="https://img.shields.io/badge/nodejs-339933.svg?&style=for-the-badge&logo=nodedotjs&logoColor=white"/> <img alt="mongodb" src ="https://img.shields.io/badge/mongodb-339933.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>

* * *
#### ⚪ Getting Strated
* ##### Prerequisites: npm, node, MongoDB Connection URL, Kakao Client ID, Google Oauth Client ID
* ##### Installation & Execution
```bash
git clone https://github.com/MpqM/NodeJS_Auth.git
# Change the .env with yours
npm install
npm start
browser: http://localhost:3000/ppauth/
```

* * *
#### ⚪ Description 
* ##### 인증 및 인가 절차 기본 흐름
 <img src="![image](https://github.com/MpqM/NodeJS_Auth/assets/79093184/ff4b7f4a-642a-42a8-8792-47400b99ed5c)"/>
● 1: 클라이언트는 유저 정보 요청을 서버에게 전송
● 2: 서버는 유저정보를 포함하는 토큰을 생성
● 3: 응답으로 클라이언트에 HTTP Response Header에 토큰을 올려서 전송
● 4: 클라이언트는 토큰을 로컬스토리지, 쿠키 등 다양한 장소에 저장
● 5: 이후 요청을 보낼때 토큰과 함께 전송
● 6: 서버 토큰을 복호화해서 유저 정보를 알게 됨

 
* ##### 페스포트와 세션을 사용한 인증 과정
 <img src="https://user-images.githubusercontent.com/79093184/260433333-0efdf916-ba4b-4483-8176-65ac26e6ae63.png"/>
 
* ##### 로그인부터 세션 저장까지 순서도
  <img src="https://user-images.githubusercontent.com/79093184/260433337-3906a4b4-1789-469d-876e-5776a8e07f53.png"/>
* ##### OAuth 프로토콜 흐름, 엑세스 토큰 만료시 리프레시 토큰을 통한 재발행
  <img src="https://user-images.githubusercontent.com/79093184/260433871-291c3293-a00f-44fc-b0ff-dbf7ece1eb3c.png"/>
* ##### 구글 OAuth 구현 순서
  <img src="https://user-images.githubusercontent.com/79093184/260433878-42222a53-f39b-44e5-a01f-acf5b0cb4c2c.png"/>
* ##### GoogleAuthGuard의 동작 순서도
  <img src="https://user-images.githubusercontent.com/79093184/260433343-a54ea8a5-58d7-442f-8d67-446c4833c1b8.png"/>
* ##### jwt관련 API테스트는 POSTMAN 파일 참조
  
* * *
#### ⚪ Roadmap & Realization & Study
* ##### 간단한 jwt인증, 쿠키세션과 PassPort를 이용한 인증 과정, MVC패턴 숙지
* ##### PassPort의 Strategy local, OAuth2.0을 활용한 구글, 카카오, ID/PW 로그인 인증
* * *
#### ⚪ Writer
* ##### <span>okqkrwhdtjd@gmail.com
* <a href = "https://github.com/MpqM"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/></a> <a href = "https://MpqM.tistory.com/"> <img alt="Tistory" src ="https://img.shields.io/badge/Tistory-white.svg?&style=for-the-badge"/></a>
* * *
#### ⚪ Contributing
* ##### Fork the Project https://github.com/MpqM/NodeJS_Auth
* ##### Create your Feature Branch (git checkout -b feature/AmazingFeature)
* ##### Commit your Changes (git commit -m 'Add some AmazingFeature')
* ##### Push to the Branch (git push origin feature/AmazingFeature)
* ##### Open a Pull Request
