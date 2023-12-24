# 빌려중고야? 

<div align="center" style="width:50px; height:50px" >
 <img width="329px" src="https://github.com/mnbvcxzyj/DBDB-deep/assets/101444425/1a485402-d3b9-40b1-a10b-72fac7017bf5" alt="joongologo" border="0">
</div>

<br/>
 
> **2023-02 데이터베이스 프로그래밍 팀 프로젝트** 


## 팀 소개

|      김예지       |          박세은         |       최다정           |            한현서           |                                                                                                  
| :------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | 
|   <img width="160px" src="https://avatars.githubusercontent.com/u/101444425?v=4"  />    |                      <img width="160px" src="https://avatars.githubusercontent.com/u/102174849?v=4" />    |                   <img width="160px" src="https://avatars.githubusercontent.com/u/80518843?v=4"/>   |                     <img width="160px" src="https://avatars.githubusercontent.com/u/80339766?v=4"/>
|   [@mnbvcxzyj](https://github.com/mnbvcxzyj)   |    [@ParkSenn](https://github.com/ParkSenn)  | [@da-jeong](https://github.com/da-jeong)  | [@hyunseo-han](https://github.com/hyunseo-han) | 

---


## 프로젝트 소개
안전한 거래인지 확신하지 못하는 불안함 속에서 금전적 거래를 해야 하는 부담감을 없애고 대화 없이 간단하게 물건을 **중고** 물품을 **빌려**주고 **대여**하는 서비스 입니다. 

---
## 화면 구성 📺
| 메인 페이지  |  물품 상세 페이지   |  빌려준 물품 페이지   |  빌린 물품 페이지  |  장바구니 페이지  | 
| :-------: | :------------: | :------------: | :------------: |  :------------: |  
|  <img width="300" src="https://github.com/mnbvcxzyj/DBDB-deep/assets/101444425/d7d84224-ff1d-414b-bb82-f7a3b0a1153a"/> |  <img width="300" src="https://github.com/mnbvcxzyj/DBDB-deep/assets/101444425/791e3072-7e53-4274-a4b8-dba06595e8fc"/>|  <img width="300" src=""/>|  <img width="300" src=""/>|  <img width="300" src="https://github.com/mnbvcxzyj/DBDB-deep/assets/101444425/816dfb66-7371-4efc-82b7-b1def9310fa1"/> | 

---
## 주요 기능 📦

### ⭐️ 회원가입/로그인/로그아웃
- 이메일을 사용하여 회원가입, 로그인 

### ⭐️ 메인 페이지 
- 물품명으로 물품 검색
- 카테고리별로 물품 목록 보기

### ⭐️ 물품 상세 페이지
- 물품 상세 정보 보기
- 물품 대여 기능
 
### ⭐️ 물품 관련 기능 
- 등록 : 물품 이름, 설명, 정가, 대여비, 보증금, 물품 카테고리, 대여 진행 장소를 입력 받아 등록 가능
- 수정
- 삭제
- 반납

### ⭐️ 거래 만족도 평가 
- 자신의 매너 점수 조회
- 거래 만족도 평가
---
## 사용 가이드
🔐 **테스트용 계정** <br/>
ID : sohee@naver.com <br/>
PW : 1234 <br/>
<br/>
ID : csp@naver.com <br/>
PW : 1234

### (1) 로그인 페이지
- 이메일로 로그인 및 회원가입을 할 수 있습니다. 

### (2) 메인 페이지
- 데이터베이스에 저장된 모든 물품들을 출력하여 보여줍니다. 
- 물품명을 입력하여 물품을 검색할 수 있습니다. 일부 키워드만 일치하더라도 물품을 검색할 수 있습니다. 
- 카테고리를 선택하여 해당 카테고리에 해당하는 물품만 볼 수 있습니다. 
- 우측 상단의 아이콘들을 클릭하여 마이페이지, 장바구니 페이지로 이동할 수 있습니다.
- 우측 상단의 물품 등록하기 버튼을 누르면 물품을 등록하는 페이지로 이동하고, 로그아웃 버튼을 누르면 로그아웃 처리됩니다. 
- 물품을 누르면 해당 물품의 상세페이지로 이동합니다.

### (3) 상세페이지 
- 물품 이름, 설명, 정가, 대여비, 보증금, 물품 카테고리, 대여 진행 장소, 빌려주는 사람의 매너온도 등의 상세 정보를 볼 수 있습니다.
- 해당 물품의 대여가 예약된 날짜들을 확인할 수 있습니다.
- 상단의 장바구니 아이콘을 누르면, 장바구니에 해당 물품이 저장됩니다. 
- 만약 자신이 등록한 물품이라면, 해당 물품을 수정하거나 삭제할 수 있습니다.

### (4) 물건 등록 페이지 
-  물품 이름, 설명, 정가, 대여비, 보증금, 물품 카테고리, 대여 진행 장소 등의 상세 정보를 입력하여 물품을 등록합니다.

### (5) 마이페이지 
- 마이페이지 메인 : 사용자의 매너점수를 확인할 수 있고 내가 빌려준 물품 페이지, 빌린 물품 페이지, 장바구니 페이지로 이동할 수 있습니다.
- 내가 빌려준 물품 : 빌려준 물품 목록을 확인하고 대여자 이름, 반납 여부등의 정보를 확인할 수 있습니다. 
- 내가 빌린 물품 : 사용자가 빌린 물품 목록을 확인하고 반납 버튼을 눌러 반납을 수행할 수 있습니다. 반납 후에는 거래 만족도 평가를 실시합니다. 
- 장바구니 : 사용자가 장바구니에 담은 물품 목록을 확인하고 삭제할 수 있습니다. 
---
