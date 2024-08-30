# 최애의 식당
![Project Introduction](readmeImages/intro.png)
- 배포 URL :  https://eataku.kr/
- Test ID : test
- Test PW : 1234


# 프로젝트 소개

## 현대인의 바쁜 일상 속에서도 간편하게, 실시간 및 날짜 예약과 식당 정보를 손쉽게 공유할 수 있는 ” 스마트 외식 플랫폼”을 소개합니다.

# 팀원 구성

| 고경호                        | 김의진                        | 서윤정                       | 좌상현                                                            | 최지수                       |
|----------------------------|----------------------------|---------------------------|----------------------------------------------------------------|---------------------------|
| 사진 <br/><br/> [@yoaruku](https://github.com/yoaruku) | 사진<br/><br/> [@dmlwls12](https://github.com/dmlwls12) | 사진  <br/><br/>[@yj0318](https://github.com/yj0318) | 사진 <br/><br/> [@sanghyeonJwa](https://github.com/sanghyeonJwa) | 사진<br/><br/> [@jisoo78](https://github.com/jisoo78) |




# 1. 개발 환경

- **Front** : HTML , CSS , JS
- **Back-end** : JAVA , Spring-Boot , Spring Security , Crawling , Python , Selenium
- **Infra** : Naver Cloud Platform , docker , Nginx , Github actions
- **API** : Naver map , coolsms
- **Database** : MySQL , JPA ,MIRO
- **Design** : Figma
- [커밋 컨벤션](https://github.com/ssg-240304-java2/final-oshi-no-restaurant/wiki/%EC%BB%A4%EB%B0%8B-%EC%BB%A8%EB%B2%A4%EC%85%98-&-%EA%B9%83-%ED%94%8C%EB%A1%9C%EC%9A%B0)


# 2. 채택한 개발 기술과 브랜치 전략



## 브랜치 전략


- **Git-flow** 전략을 기반으로 main,develop 브랜치와 feature 보조 브랜치를 운용했습니다.
  - **main** 브랜치는 배포 단계에서만 사용하는 브랜치 입니다.
  - **develop** 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
  - **feature** 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 , 각 브랜치를 삭제해 주었습니다.


# 3. 프로젝트 구조


최종 완료되면   인텔리제이에서 뽑기


# 4.역할 분담

## 고경호
- **UI**
  - 페이지 : Header, Footer , 알림 창 , 사용자 회원 가입 페이지
- **기능**
  - 회원 가입 , 알림 , 검색 ,추천
  

## 김의진

- **UI**
    - 페이지 : 레스토랑  페이지 
- **기능**
    - 매장관리 , 예약 관리자 


## 서윤정

- **UI**
    - 페이지 : 예약페이지, 예약 확정 ,예약 취소 , 상세 페이지
- **기능**
    -  회원 예약 , 리뷰 등록 

## 좌상현

- **UI**
  - 페이지 : 웨이팅 페이지
- **기능**
  - 회원 웨이팅 , 관리자 웨이팅


## 최지수

- **UI**
    - 페이지 : 리스트 페이지 , 리뷰 페이지
- **기능**
    - 리뷰 수정 및 삭제 , 리스트 생성, 수정 , 삭제


# 5. 개발 기간 및 작업 관리

## 개발기간

- 전체 개발 기간 : 2024-07-19 ~ 2024-09-02
- UI 개발 : 2024-07-29 ~ 2024-08-05
- Backend 개발 : 2024-08-06 ~ 2024-08-30
- ERD 개발 : 2024-07-30 ~ 2024-08-02


## 6. ERD




## 7.작업 관리

- [Notion](https://coffit23.notion.site/3-oshi_no_restaurant-4deeb7b1685547cc96e80c2256969737) , Github Projects 와 Issues를 사용하여 진행 사항을 공유 했습니다.
- 주간회의를 진행하며 작업 순서와 방향성에 대한 고민을 나누고 Notion 캘린더에 회의 내용을 기록했습니다.


# 6. 주요 기능



## 회원, 매장 , 소셜 로그인
<img src="readmeImages/회원-매장-소셜-로그인-완료.gif" alt="회원-매장-소셜-로그인-완료" width="300"/>

## 웨이팅 등록과 리뷰 등록
<img src="readmeImages/웨이팅 등록과 리뷰 등록.gif" alt="웨이팅 등록과 리뷰 등록" width="300"/>

## 예약 등록 및 예약 취소
<img src="readmeImages/예약 등록 및 예약 취소.gif" alt="예약 등록 및 예약 취소" width="300"/>

## 리뷰 작성
<img src="readmeImages/리뷰작성.gif" alt="리뷰작성" width="300"/>

# 7. 트러블 슈팅

- [예약 이슈](https://github.com/ssg-240304-java2/final-oshi-no-restaurant/wiki/%EC%98%88%EC%95%BD-%EC%9D%B4%EC%8A%88) 
- [웨이팅 이슈](https://github.com/ssg-240304-java2/final-oshi-no-restaurant/wiki/%EC%9B%A8%EC%9D%B4%ED%8C%85-%EC%9D%B4%EC%8A%88)
- [리스트 이슈](https://github.com/ssg-240304-java2/final-oshi-no-restaurant/wiki/%EB%A6%AC%EC%8A%A4%ED%8A%B8-%EC%9D%B4%EC%8A%88)
- [리뷰 이슈](https://github.com/ssg-240304-java2/final-oshi-no-restaurant/wiki/%EB%A6%AC%EB%B7%B0-%EC%9D%B4%EC%8A%88)
- [멤버 이슈](https://github.com/ssg-240304-java2/final-oshi-no-restaurant/wiki/%EB%A9%A4%EB%B2%84-%EC%9D%B4%EC%8A%88)


# 8. 개선목표




# 9.프로젝트 후기

## 고경호



## 김의진




## 서윤정

시나리오대로 구현한 점은 좋았지만 아쉬운 점은 시나리오 외적인 상황에 대해 충분히 고려하지 못했다는 것입니다. 이로 인해 예기치 않은 상황에 대비하거나 즉각적으로 대응하는 데 어려움이 있었습니다. 앞으로는 시나리오 내의 계획을 철저히 준비하는 것뿐만 아니라, 다양한 가능성을 염두에 두고 예상치 못한 상황에서도 유연하게 대처할 수 있는 능력을 기르는 것이 중요하다는 것을 느꼈습니다. 



## 좌상현




## 최지수












