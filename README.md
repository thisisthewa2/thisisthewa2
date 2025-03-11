![e1343abc-fd91-455e-b544-8f2f8bbfb139](https://github.com/user-attachments/assets/bee8dac4-d1d3-46f8-8cba-cc76d863549d)

### 👋 프론트엔드 개발자 안윤진입니다. 
### 블로그 : https://velog.io/@heresyoonjin/posts
 
### 참여한 프로젝트 
  
#### 술닥술닥 — 즐거운 술 문화를 위한 플랫폼
2024.06. ~ 진행 중
사용한 기술 스택 - TypeScript, React, Next.js, tailwind css, react-query
담당
-  술 검색을 위한 웹뷰 개발 및 배포 (배포링크: https://webview.suldak.co.kr/liquor/search  깃허브: https://github.com/suldak/suldak-webview )
react-query 커스텀훅을 사용해 최신 검색어 받아오기 및 삭제, 검색어 랭킹과 추천검색어 연결 구현
검색 시 결과 화면으로 라우트 후 useSearchParams를 사용해 검색어 필터링 후 검색결과 렌더링
- 앱 가이드 웹뷰 (https://webview.suldak.co.kr/guide)
useRef와 Intersection Observer를 사용해 스크롤 위치 조작 & 현재 스크롤 위치를 탭바에 상태반영
- 랜딩페이지 (배포링크: https://www.suldak.me/ 깃허브: https://github.com/suldak/web-mono )
pnpm 환경으로 마이그레이션
사전예약 api 연결 및 팀원소개, 문의를 위한 페이지들을 반응형 구현


#### Readme — 커뮤니티 기능이 결합된 도서 판매 커머스
2024.01. ~ 2024.02 (현재 배포중단)
사용한 기술 스택 - TypeScript, React, Next.js, tailwind css, react-query
깃허브 링크: https://github.com/bookstore-README/front_bookstore-README 
담당
-  메인페이지
react-query 커스텀훅을 사용해 도서 정보 api 연결, 반응형 UI
-  결제
포트원 테스트 결제 api 연결을 통한 결제 기능 구현
Jotai를 사용해 전역변수로 주문 내역 저장
- 공통컴포넌트 제어
로그인 여부 / 페이지별 분기에 따라 컴포넌트 제어



