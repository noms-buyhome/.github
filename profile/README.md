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
    

## 📖 서비스 구현 화면


### 매물 검색


- 지도를 움직일 때 현재 표시하고 있는 주소 갱신
- 현재 주소 기준 동별 매물 마커 표시 및 리스트 출력

![서비스구현화면_매물검색](https://user-images.githubusercontent.com/101002050/209335152-1ce8289c-4c74-4eee-af97-3d7df0e07d86.png)

### 주변 상권 정보 표시


- 카카오 로컬 Rest API를 이용하여 지도 중심 기준 2km 반경의 주변 상권을 지도에 개별의 마커로 표시

![서비스구현화면_주변상권](https://user-images.githubusercontent.com/101002050/209335149-473ab955-8393-4c32-a7ee-cdae067776bd.png)

### 매물 정보 조회
---
- 해당 매물의 대략적인 정보, 실거래가 거래내역 조회

![서비스구현화면_매물정보](https://user-images.githubusercontent.com/101002050/209335146-04fc444d-842d-4482-bc34-54e3817cea48.png)


**QNA게시판**

- 게시글 CRUD
- 게시글 좋아요 기능

**로그인**

- JWT 토큰을 이용한 로그인 구현
- 필터를 통해 토큰을 검증하고 유효하지 않은 토큰일 경우 예외 발생

## 📆프로젝트 일정


![프로젝트일정](https://user-images.githubusercontent.com/101002050/209335144-08c346e6-929a-4991-85e4-b0c2540b6062.png)

## 🔧개발 환경


### FrontEnd

![개발환경_HTML,CSS,JS](https://user-images.githubusercontent.com/101002050/209335142-8c09be40-18a3-48bd-a193-d7f36b579205.png)

![개발환경_Vue](https://user-images.githubusercontent.com/101002050/209335141-823f595d-7577-41af-9c41-f24ee9d30d17.png)

### BackEnd

![개발환경_SpringBoot](https://user-images.githubusercontent.com/101002050/209335137-2c6cb15b-45d2-402a-aeda-44b86cfbfd60.png)

![개발환경_MyBatis](https://user-images.githubusercontent.com/101002050/209335134-7d9d7270-3114-402b-86cb-752e806f95f9.png)

![개발환경_MySQL](https://user-images.githubusercontent.com/101002050/209335130-cf58a08f-1cae-4108-943c-91a07568fcd9.png)
