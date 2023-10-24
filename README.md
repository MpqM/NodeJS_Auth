# Auth
⚪ **About Project / Description**
 * jwt 엑세스토큰, 리프레시토큰 사용 인증 구현
 * 쿠키세션 + PassPort(Strategy, Session Serializer, deSerializer)를 사용한 인증 구현
 * jwt, passport를 통해 인증받은 사용자 만이 리소스에 접근하게 하는 미들웨어 구현
 * Mongoose를 이용해 Oauth ID 및 사용자 정보 모델, P/W 함수(저장 전 해싱, 비교) 정의
* * *

⚪ **Usage**
<p align ="center">
  [NodeJS_Auth](https://www.youtube.com/watch?v=vQkZ0dgmi9I)
  ![image](https://user-images.githubusercontent.com/79093184/268300607-ec6350cc-e75c-4796-b58d-3ce3a4182c51.png)
</p>

* * *

⚪ **Built With**
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
* ##### JWT기반 인증 인가 과정
<img src="https://user-images.githubusercontent.com/79093184/268309865-786a47dc-375f-4eae-bf8e-1834a2a7002c.png"/>

* ##### 엑세스, 리프레시 토큰 흐름
<img src="https://user-images.githubusercontent.com/79093184/268310086-41f36848-0fa9-4de2-b80b-019cb2eacc1b.png"/>

* ##### Passport를 이용한 쿠키 세션 과정
<img src="https://user-images.githubusercontent.com/79093184/268310220-7ddbc695-f9a4-4231-88bd-53142ffda367.png"/>
  
* ##### Oauth 흐름
<img src="https://user-images.githubusercontent.com/79093184/268310369-5082e1e3-b6f9-4847-a262-fdf04b637dcf.png"/>

* ##### jwt관련 API테스트는 POSTMAN 파일 참조, 자세한 내용은 소스코드 주석 참조
  
* * *
#### ⚪ Roadmap & Realization & Study
* ##### 간단한 jwt인증, 쿠키세션과 PassPort를 이용한 인증 과정, MVC패턴 숙지
* ##### 타입스크립트를 사용안한 MongoDB 모델 정의를 처음 해봄
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
