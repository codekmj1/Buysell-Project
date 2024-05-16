# Buysell

## 목차
1. [프로젝트 소개](#프로젝트-소개)
2. [팀소개](#팀소개)
3. [프로젝트 계기](#프로젝트-계기)
4. [주요기능](#주요기능)
5. [개발기간](#개발기간)
6. [기술스택](#기술스택)
7. [서비스 구조](#서비스-구조)
8. [와이어프레임](#와이어프레임)
9. [API 명세서](#api-명세서)
10. [ERD](#erd)
11. [프로젝트 파일 구조](#프로젝트-파일-구조)
12. [기술적 의사결정](#기술적-의사결정)
13. [트러블 슈팅](#트러블-슈팅)
    
## 프로젝트 소개
중고 거래 플랫폼으로 개인 간의 중고 거래를 더욱 쉽게 접근할 수 있게 매칭해주는 게시판 형태의 서비스입니다. 

중고 물품을 판매하는 글을 작성할 수 있고 구매자가 구매 요청을 하면 판매자와 구매자가 매칭 됩니다.

## 팀소개
|<img src=https://github.com/HwangSeungHyeon/buysell/assets/57141923/e5b7d730-9287-4693-aea9-9897b838697b width=150px height=150px>|<img src=https://github.com/HwangSeungHyeon/buysell/assets/57141923/02631b02-1f0c-4df0-bfbb-0968e058e65e width=150px height=150px>|<img src=https://github.com/HwangSeungHyeon/buysell/assets/57141923/30556bb0-f64f-4f87-a715-219e4fb1e10e width=150px height=150px>|<img src=https://github.com/HwangSeungHyeon/buysell/assets/57141923/5f539a96-b38f-4126-96ac-ba36d989bdfb width=150px height=150px>|
|:---:|:---:|:---:|:---:|
|**팀장**|**부팀장**|**팀원**|**팀원**|
|김성현|황승현|김민주|김현주|
|[lazzykim](https://github.com/lazzzykim)|[HwangSeungHyeon](https://github.com/HwangSeungHyeon)|[codekmj1](https://github.com/codekmj1)|[hyunzoo123123](https://github.com/hyunzoo123123)|
|**게시글, 리뷰, 결제**|**댓글, 검색, 배포, 위시리스트**|**인증, 인가, 소셜 로그인**|**프로필, 프론트**|


## 프로젝트 계기
최근에는 미니멀 라이프가 유행하면서 많은 사람들이 소유물을 정리하고 불필요한 물건을 줄이는 추세에 있습니다.

이러한 환경 변화 속에서 중고 거래 플랫폼은 판매자와 구매자가 함께 이익을 얻을 수 있는 효율적인 방법으로 부상하고 있습니다. 

중고 거래는 더 이상 사용하지 않는 물건을 버리는 것이 아니라 재활용하고 다시 이용함으로써 자원을 절약하고 환경을 보호하는데 기여합니다.

이 서비스를 통해 개인 및 비즈니스적인 부분에서도 긍정적인 영향을 끼칠 것으로 생각되어 프로젝트를 선정하게 되었습니다.

## 주요기능

- 이메일과 비밀번호를 이용한 로그인
- 소셜 로그인: 카카오, 네이버, 구글
- 자기 프로필 수정
- 회원 탈퇴
- 판매 게시글 등록, 수정, 삭제
- 댓글 등록, 수정, 삭제
- 자신이 등록한 게시글 목록 확인
- 다른 사람의 판매 제품 구매
- 판매자 평점 확인
- 판매자 게시글 목록 확인

## 개발기간
- 2024.02.26(월) ~ 2024.04.04(목)

## 기술스택

### ✔️ Language
<img src="https://img.shields.io/badge/kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">

### ✔️ Version Control
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">

### ✔️ IDE
<img src="https://img.shields.io/badge/intellij idea-000000?style=for-the-badge&logo=intellijidea&logoColor=white">

### ✔️ Framework
#### Backend : <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/spring security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
#### Frontend : <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white"> <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">

### ✔️ Deploy
#### Backend : <img src="https://img.shields.io/badge/amazon ec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
#### Frontend : <img src="https://img.shields.io/badge/vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
### ✔️ Local DBMS
<img src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">

### ✔️ Cloud DBMS
#### Backend : <img src="https://img.shields.io/badge/amazon rds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white">
#### Frontend : <img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"> 

## 서비스 구조
![BuySell 시스템 아키텍처 (1)](https://github.com/HwangSeungHyeon/buysell/assets/57141923/4cc8fd5b-a6d7-4353-8ced-a85e98725e40)


## 와이어프레임
![Wandering](https://github.com/HwangSeungHyeon/buysell/assets/57141923/7236fe2b-33d6-4959-a56c-437d6f4a0b01)


## API 명세서
<details>
<summary> 멤버 API 명세서 </summary>
<div markdown="1">
  <img src= https://github.com/HwangSeungHyeon/buysell/assets/57141923/270ebc87-141d-45b6-a1d4-33b9017430f9>
</div>
</details>

<details>
<summary> 프로필 API 명세서</summary>
<div markdown="1">
  <img src= https://github.com/HwangSeungHyeon/buysell/assets/57141923/d1d0c5eb-2a62-476c-b960-2cf95e453d10>

</div>
</details>

<details>
<summary> 계좌 API 명세서</summary>
<div markdown="1">
  <img src= https://github.com/HwangSeungHyeon/buysell/assets/57141923/f6aa240c-8592-404b-b215-f4621fe41e64>
</div>
</details>

<details>
<summary> 게시글 API 명세서</summary>
<div markdown="1">
  <img src= https://github.com/HwangSeungHyeon/buysell/assets/57141923/c8299100-aa94-41d4-a4e0-1ead7c28bfa3>
</div>
</details>

<details>
<summary> 댓글 API 명세서</summary>
<div markdown="1">
  <img src= https://github.com/HwangSeungHyeon/buysell/assets/57141923/baae2df3-0234-49e9-9697-60858837d126>

</div>
</details>

<details>
<summary> 리뷰 API 명세서</summary>
<div markdown="1">
  <img src= https://github.com/HwangSeungHyeon/buysell/assets/57141923/395c1b83-99c4-454a-a176-d8d7fa535b30>
</div>

</details>

## ERD
![최종프로젝트 ERD](https://github.com/HwangSeungHyeon/buysell/assets/57141923/4ac752ce-e76c-4854-ac26-bd4b615bce69)


## 프로젝트 파일 구조
#### Backend
```
buysell
    ├─domain
    │  ├─comment
    │  │  ├─controller
    │  │  ├─dto
    │  │  │  ├─request
    │  │  │  └─response
    │  │  ├─model
    │  │  ├─repository
    │  │  └─service
    │  ├─common
    │  │  └─dto
    │  ├─exception
    │  │  └─dto
    │  ├─member
    │  │  ├─controller
    │  │  ├─dto
    │  │  │  ├─request
    │  │  │  └─response
    │  │  ├─model
    │  │  ├─repository
    │  │  └─service
    │  ├─order
    │  │  ├─controller
    │  │  ├─dto
    │  │  │  └─request
    │  │  ├─model
    │  │  ├─repository
    │  │  └─service
    │  ├─post
    │  │  ├─controller
    │  │  ├─dto
    │  │  │  ├─request
    │  │  │  └─response
    │  │  ├─model
    │  │  ├─repository
    │  │  └─service
    │  └─review
    │      ├─controller
    │      ├─dto
    │      │  ├─request
    │      │  └─response
    │      ├─model
    │      ├─repository
    │      └─service
    └─infra
        ├─auditing
        ├─querydsl
        ├─redis
        ├─security
        │  └─jwt
        ├─social
        │  └─jwt
        └─swagger
```
#### Frontend
```
├─assets
│  ├─css
│  ├─fonts
│  ├─img
│  │  ├─examples
│  │  ├─illustrations
│  │  ├─logos
│  │  │  ├─gray-logos
│  │  │  ├─medium-logos
│  │  │  ├─small-logos
│  │  │  └─white-logos
│  │  ├─shapes
│  │  └─small-logos
│  ├─js
│  │  ├─core
│  │  └─plugins
│  │      └─presentation-page
│  └─scss
│      └─material-kit
│          ├─bootstrap
│          │  ├─forms
│          │  ├─helpers
│          │  ├─mixins
│          │  ├─utilities
│          │  └─vendor
│          ├─cards
│          ├─custom
│          ├─forms
│          ├─mixins
│          ├─plugins
│          │  └─free
│          └─variables
├─components
├─examples
│  ├─cards
│  │  ├─blogCards
│  │  ├─counterCards
│  │  ├─infoCards
│  │  ├─reviewCards
│  │  ├─rotatingCards
│  │  └─teamCards
│  ├─footers
│  ├─navbars
│  └─tables
├─layouts
│  └─sections
│      ├─attention-catchers
│      │  ├─alerts
│      │  │  └─components
│      │  ├─modals
│      │  │  └─components
│      │  └─tooltips-popovers
│      │      └─components
│      ├─components
│      ├─elements
│      │  ├─avatars
│      │  │  └─components
│      │  ├─badges
│      │  │  └─components
│      │  ├─breadcrumbs
│      │  ├─button-groups
│      │  │  └─components
│      │  ├─buttons
│      │  │  └─components
│      │  ├─dropdowns
│      │  │  └─components
│      │  ├─progress-bars
│      │  │  └─components
│      │  ├─toggles
│      │  │  └─components
│      │  └─typography
│      │      └─components
│      ├─input-areas
│      │  ├─forms
│      │  │  └─components
│      │  └─inputs
│      │      └─components
│      ├─navigation
│      │  ├─nav-tabs
│      │  │  └─components
│      │  ├─navbars
│      │  │  └─components
│      │  └─pagination
│      │      └─components
│      └─page-sections
│          ├─features
│          │  └─components
│          └─page-headers
│              └─components
├─router
├─stores
├─utils
└─views
    ├─LandingPages
    │  ├─AboutUs
    │  │  └─Sections
    │  ├─Author
    │  │  └─Sections
    │  ├─components
    │  ├─ContactUs
    │  ├─posts
    │  └─SignIn
    ├─MySales
    ├─Pay
    │  └─Components
    ├─Presentation
    │  ├─Components
    │  └─Sections
    │      └─Data
    └─WishList
```

## 기술적 의사결정

<details>
<summary> RDS </summary>
<div markdown="1">
[도입 이유]</br>
      - 비교적 빠르게 인스턴트를 생성하고 구성할 수 있음</br>
      - 필요에 따라 스토리지 용량을 확장할 수 있어 확장성이 높음</br>
      - IAM으로 접근권한을 세밀하게 관리할 수 있음</br>
      - 다양한 DB엔진 지원</br>
[문제상황]</br>
      - AWS 서비스에 대한 사용법을 익히는데 시간이 필요함</br>
      - 다양한 옵션들의 과금정책이 복잡해 현재 상황에서 예상 비용을 계산하기 어려움</br>
[해결방안]</br>
      - AWS 관련 자료는 다른 Cloud DB에 비해 방대한 양의 참고자료가 있기에 대부분의 문제는 검색으로 해결 가능</br>
      - AWS 비용 계산기를 사용해 사전에 예상비용을 계산하고 필요에 따라 리소스를 조정해야함</br>
[의사 결정]</br>
      - AWS 강의와 자료검색들을 통해 학습시간을 최대한 단축</br>
      - 비용계산기로 대략적인 금액 계산 후 배포기간과 정해진 예산 이내로 리소스 조정</br>
      - 검색 시 제공되는 자료의 양이 많은 Amazon RDS 채택</br>
</div>
</details>

<details>
<summary> ElastiCache </summary>
<div markdown="1">
[도입 이유]</br>
      - 회원 가입 시 실제로 존재하는 이메일인지 확인 하기 위함</br>
[문제상황]</br>
      - 이메일 인증 번호 저장 위치에 대한 결정 필요</br>
[해결방안]</br>
      - Redis와 AWS RDS를 후보로 삼아 비교하고 평가하기로 함</br>
[의사 결정]</br>
      - 인증 번호는 DB에 자주 접근하기 때문에, 사용자가 늘어날 경우 DB에 부담을 줄 수 있음</br>
      - 이메일 인증코드는 임시 데이터이기 때문에 임시데이터를 관리하는 측면에서 Redis를 사용하는것이 유리</br>
      - 빠른 속도와 자동 만료기능, 확장성에서 Redis가 우수하다고 판단해 채택</br>
</div>
</details>

<details>
<summary> Security</summary>
<div markdown="1">
[도입 이유]</br>
      - 온라인 플랫폼을 운영하는데 있어서 사용자 관리의 정교함이 중요하다 판단됨</br>
      - 필요한 데이터에 안전하고 빠르게 접근하도록 지원, 동시에 고객 데이터를 효율적으로 관리하는데 도움이 된다고 판단하여 도입함</br>
[문제상황]</br>
      - 다양한 보안 위험에 노출되어 있기 때문에 공격으로부터 웹 애플리케이션을 보호해야 될 필요가 있음</br>
      - 사용자 인증 및 세밀한 권한 관리는 구현하기 복잡하여 이를 위한 효율적인 솔루션이 필요함</br>
[해결방안]</br>
      -  Spring Security를 도입하여 포괄적인 보안 솔루션을 제공 받아 보안 강화 </br>
      - Spring Security의 다양한 보안 설정으로 애플리케이션의 특정 요구 사항에 맞게 보안 정책을 조정</br>
[의사 결정]</br>
      - 보안 정책과 관련하여 팀 내에서 충분한 논의를 거치면서 Spring Security의 도입이 애플리케이션에 미치는 영향과 이점을 공유할 수 있어서 spring security 채택</br>
</div>
</details>

<details>
<summary> CI/CD </summary>
<div markdown="1">
[도입 이유]</br>
      - 코드 오류를 초기에 찾고 배포에 걸리는 시간을 줄이기 위함</br>
[문제상황]</br>
      - CI를 적용하지 않고 수동으로 테스트를 했더니 시간이 많이 소요됨</br>
      - CD 미적용 시,  서버에 직접 JAR 파일 배포되는 시간이 지연 되어 검토도 지연 됨</br>
[해결방안]</br>
      - Github Actions를 이용</br>
      - Jenkins를 이용</br>
[의사 결정]</br>
      - CI/CD 서버가 내장되어 있어서 CI/CD 서버를 구축할 필요가 없음</br>
      - Github에 내장되어 있기 때문에 Github와 통합이 쉬움</br>
      - GitHub와의 자연스러운 연동으로 향상된 생산성을 제공하는 Github Actions를 사용</br>
</div>
</details>

## 트러블 슈팅
### **🚨문제 배경**

카카오 소셜로그인 기능 구현 중 발급 받은 엑세스 토큰이 유효하지 않는 문제가 발생.

이메일 값이 NULL로 들어가서 로그인 한 이메일 값과 일치하지 않기 때문.

### **⌛시도 했던 방법들**

- 구글링을 통해 비슷한 이슈를 해결한 사람이 있는지 조사.
- 이메일 값을 가져오는 과정을 알아보기 위해 intellij 디버그 모드 사용.

### **🙌이전 코드와 비교**

이전 코드는 구글 소셜로그인 이메일 값 가져오는 코드와 같음.

디버깅을 통해 카카오 소셜로그인은 이메일 값이 들어있는 attribute가 다른 것을 확인.

코드 수정 결과 정상적으로 이메일 값을 가져오는 것을 확인.

- **이전 코드**

![스크린샷 2024-05-10 160216.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c7ff9390-c087-4427-81f4-c6d19a2c879f/c98215bf-9fef-48e6-9718-2d96504178f9/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-05-10_160216.png)

- **수정된 코드**

![스크린샷 2024-05-10 160253.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c7ff9390-c087-4427-81f4-c6d19a2c879f/b7eea3ad-7039-425a-8ef9-5c8b917c86a3/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-05-10_160253.png)

### **🌟알게 된 점**

소셜로그인 플랫폼 마다 이메일 값을 저장하고 있는 경로가 다르다는 것과, 이메일 값이 들어있는 경로를 코드로 작성해야 정상적으로 이메일 값을 가져올 수 있다는 것을 알게 됨.

![스크린샷 2024-05-10 164516.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c7ff9390-c087-4427-81f4-c6d19a2c879f/b60e55a0-2161-493d-9480-e7db949702c2/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-05-10_164516.png)

**구글 소셜로그인 이메일 값 경로**

![스크린샷 2024-05-10 164620.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c7ff9390-c087-4427-81f4-c6d19a2c879f/41f5917b-313d-4672-b79d-b34885505c84/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-05-10_164620.png)

**카카오 소셜로그인 이메일 값 경로**

