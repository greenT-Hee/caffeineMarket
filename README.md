# caffeineMarket

## **☕ 프로젝트 소개**

스토어에 판매하고 있는 상품을 등록하여 홍보할 수 있는 SNS입니다.
상품을 등록하지 않아도 일상을 공유하며 즐거운 SNS 활동을 할 수 있습니다.
사용자는 글과 사진을 올려 자신의 일상을 공유할 수 있고,
다른 사용자를 팔로우하여 홈 화면에서 다른 사람들의 소식을 확인할 수도 있습니다.
다양한 사람들을 팔로우하고, 마음에 드는 피드가 있다면 '좋아요'를 누르거나 댓글을 달 수도 있습니다.
또한, 다른 사용자와 채팅창을 이용해 즐거운 대화도 나눌 수 있습니다.

## :fire: 팀 : 2호선 불주먹

김지수, 김민영, 채지훈, 김태희


## 1. 목표
- API를 이용한 SNS 프론트엔드 개발 구현.


## 2. 개발 환경 및 배포
### 2.1 스택

HTML
CSS
JavaScript

## 3. 프로젝트 구조와 개발 일정
### 3.1 프로젝트 구조
```
.
├──📁 node_modules
├──📁 src
│   ├──📁 pages
│   │   ├── template
│   |   └── ...html
│   ├──📁 css
│   ├──📁 img
│   └──📁 js
│      
├──📁 router
│   ├── market.js
└── app.js
```

### 3.2 개발일정
기간 : 
HTML/CSS 
JavaScript 

## 4. 역할 분담

### 김지수
- 로그인 창
- 사용 API

### 김민영
- 게시글 피드
- 사용 API
   - 게시글 API

### 채지훈
- 상품 등록 / 채팅창
- 사용 API
  - 이미지(한 개의 이미지)

### 김태희
#### 1)  myProfile & yourProfile 
- 유저 정보 API GET 
- 상품 리스트 API GET, DELETE
- 게시글 리스트 API GET, DELETE
- 공용 및 프로필 모달 제작 및 기능 구현
- 로그아웃 기능 구현

#### 2) follwing & follower (진행중)
- 팔로잉/ 팔로우 리스트 보여주기
- 팔로우 버튼 누르면 숫자 증가  
- 팔로우 취소 버튼 누르면 숫자 감소

