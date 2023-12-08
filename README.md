# BlueHorizon - 2023.11 팀프로젝트
##### 사용기술
- Spring
- MyBatis
- MySql
- html
- css
- jQuery
- JS

---
## DB 테이블생성 구문 및 sql구문 관련
##### DB(테이블/sql) zip파일
[BlueHorizon 관련 tripteamDb생성 구문 및 관련 sql 구문.zip]
(https://github.com/Shimhyeoungjune/BlueHorizon/files/13556713/BlueHorizon.tripteamDb.sql.zip)


---


## 역할
##### 백엔드
- 로그인,회원가입, 회원정보수정, 회원탈퇴

---
## 회원가입 페이지 작업
##### - 회원가입
![image](https://github.com/Shimhyeoungjune/BlueHorizon/assets/146051549/4779ffd7-35f5-4c81-963e-f8f5d6364090)

- 아이디 중복검사시 해당ID 가 DB에 없으면 "사용가능한 아이디입니다." 메세지띄워주고, 있으면 "이미 사용중인 아이디입니다." 라는 메세지를 띄워줍니다.
- 중복검사,유효성검사완료하고 회원가입 클릭하면 하면 DB에 새로운 데이터가 저장됩니다.
---
<br>

## 로그인 페이지 작업
##### - 로그인
![image](https://github.com/Shimhyeoungjune/BlueHorizon/assets/146051549/058a35d8-5e8a-49d9-945c-cfc6c8a31247)

- 로그인 버튼 클릭시 입력한ID가 DB에 있는 ID 인지 확인하고 있으면 "로그인 되었습니다." 메세지띄워주고, 없으면 "일치하는 회원정보가 없습니다."라는 메세지를 띄워줍니다.
---
<br>

## 아이디찾기 페이지 작업
##### - 아이디찾기
![image](https://github.com/Shimhyeoungjune/BlueHorizon/assets/146051549/96cf5bd2-a3c3-4924-86cf-9030b47c1321)

- 아이디찾기버튼 클릭시 아이디찾기 페이지 나오고  이름과 이메일을 입력해서 DB에 데이터가있으면 해당정보의 ID를 알려줍니다.
  데이터가 없으면 "조회결과가 없습니다." 라고 알려줍니다.
---
<br>

## 비밀번호찾기 페이지 작업
##### - 비밀번호찾기
![image](https://github.com/Shimhyeoungjune/BlueHorizon/assets/146051549/787e192b-f748-4da1-b05e-513ea3753845)

- 비밀번호 찾기 페이지에서 ID,이름,이메일 입력해서 DB에 해당 정보가 있는지 확인한후 있으면 임의의 비밀번호를 생성해 DB에있는 해당정보의 비밀번호를
  임시비밀번호로 변경시켜준다.

---
<br>

## 회원정보수정 페이지 작업
##### - 회원정보수정
![image](https://github.com/Shimhyeoungjune/BlueHorizon/assets/146051549/5df58150-e1e0-42ad-9cda-c15f7cb801e5)

- 새비밀번호, 핸드폰번호, 이메일란 입력시 해당ID의 DB에있는 비밀번호, 핸드폰번호, 이메일 데이터값들이 변경됩니다.

---
<br>

## 회원탈퇴 페이지 작업
##### - 회원탈퇴
![image](https://github.com/Shimhyeoungjune/BlueHorizon/assets/146051549/cf2b0214-c0df-459b-a965-5432b4680984)

- 회원탈퇴 클릭시 비밀번호 확인하는 팝업창이 나오고, 로그인한ID의 DB에있는 비밀번호 와 일치시 회원탈퇴 처리가됩니다.
