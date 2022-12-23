# 집 사 (Buy Home) 🏠

- **SAFFY 8기 1학기 최종 관통 프로젝트**
- **진행 기간** : 2022.11.17 ~ 2022.11.24
- **목표**
    - 주택 거래 정보 검색 및 주변 상권 정보 제공 서비스.
    - 사용자에게 부동산 관련된 커뮤니티를 제공합니다.

## 👍TEAM

- **노정환**
    - 주택 거래내역, 매물 정보 조회 기능 구현
    - 카카오맵 API, 카카오로컬 Rest API을 통한 매물, 주변 상권 마커 표시 기능 구현
    - 프로젝트 관련 자료 문서화
- **오민성**
    - QNA 게시판 기능 구현
    - JWT 로그인 관련 기능 구현
    

## **🪟 서비스 구현 화면**


### 매물 검색


- 지도를 움직일 때 현재 표시하고 있는 주소 갱신
- 현재 주소 기준 동별 매물 마커 표시 및 리스트 출력

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fc8ac104-16f1-4237-b584-a256fc961c26/Untitled.png)

### 주변 상권 정보 표시


- 카카오 로컬 Rest API를 이용하여 지도 중심 기준 2km 반경의 주변 상권을 지도에 개별의 마커로 표시

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9269ccc0-6abe-4236-83e1-3a22cac732a5/Untitled.png)

### 매물 정보 조회


- 해당 매물의 대략적인 정보, 실거래가 거래내역 조회

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1750bd85-8334-45a6-8edd-87db8ddb8efb/Untitled.png)

위에서 작성했던 것처럼 아래도 구현한 기능 쓰고 기능 대략적인 설명, 기능 구현화면 스크린샷 써놓으면 됨

**QNA게시판**

- 게시글 CRUD
- 게시글 좋아요 기능

**로그인**

- JWT 토큰을 이용한 로그인 구현
- 필터를 통해 토큰을 검증하고 유효하지 않은 토큰일 경우 예외 발생

## 📆프로젝트 일정


![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/822d5abf-7155-438d-a40d-d3b0dda26e08/Untitled.png)

## 🔧개발 환경


### FrontEnd

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/51429828-9492-47f6-9a92-6fccc5f9cfba/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a7055ed5-5cbb-4d13-b437-c2f97ac89486/Untitled.png)

### BackEnd

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d4970f82-13c1-49bc-a0d3-66bbc23cf085/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c4eaef64-6ed4-4f8e-bbab-4c274a745599/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5cf82b7a-8006-4275-b45a-c03ded193728/Untitled.png)
