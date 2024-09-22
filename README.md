![e1343abc-fd91-455e-b544-8f2f8bbfb139](https://github.com/user-attachments/assets/bee8dac4-d1d3-46f8-8cba-cc76d863549d)

### 👋 프론트엔드 개발자 안윤진입니다. 
### 블로그 : https://velog.io/@heresyoonjin/posts
<details> 
<summary> 
  
### 최근 참여한 프로젝트
</summary>

#### 술 모임 커뮤니티 앱'술닥술닥' 협업개발 (출시예정)
<img src="[https://github.com/thisisthewa2/thisisthewa2/assets/119280160/3a6df636-2691-4e28-ba6f-5beda5627109](https://github.com/user-attachments/assets/d4836e73-70dc-44f1-b8cc-b4af00929038)" width="300" height="200"/>


사용한 기술 스택: <img src="https://img.shields.io/badge/nextjs-000000?style=for-the-badge&logo=next.js&logoColor=white"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"> <img src="https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=white">  <img src="[https://img.shields.io/badge/axios-5a29e4?style=for-the-badge&logo=axios&logoColor=white](https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactQuery&logoColor=white)"> <img src="[https://img.shields.io/badge/reacthookform-ec5990?style=for-the-badge&logo=reacthookform&logoColor=white](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)">

<details>
<summary> 기여 </summary>
  
- 술 검색 웹뷰: useSearchParams를 사용해 검색 api 연결
- 앱 가이드 웹뷰: useRef와 Intersection Observer를 사용해 스크롤 위치 조작 & 현재 스크롤 위치를 탭바에 상태반영
- 랜딩페이지: useRef를 사용해 스크롤 위치 조작, 이미지 캐러셀 구현, 사전예약을 위한 api 연결
  
</details>
<details>
<summary> 배운점 </summary>
  
1. 검색결과를 렌더링하는 문제: 페이지 이동 후 Next.js의 useSearchParams훅을 사용해 검색 파라미터를 읽어 검색 훅을 호출하도록 했습니다.
2. 사전예약 등록 에러 처리: react-query의 useMutation을 사용하여 등록이 제대로 처리되지 않은 경우 사용자에게 토스트를 띄우도록 했습니다.
3. 최근검색어 삭제를 즉시 반영해야하는 문제: invalidateQueries를 통해 캐시를 무효화하도록 해 사용자가 최근 검색어를 삭제할 때마다 즉시 UI에 반영되도록하였습니다.
4. 검색 필터 팝업을 내부 상태관리에서 개별 페이지로 이전하는 문제: 내부 상태관리로 필터 팝업을 구현했었으나 추후 SEO최적화 문제를 고려하여 페이지를 별도의 페이지로 분리했습니다. 병렬 라우팅을 통해 정렬 버튼을 클릭하는 경우에만 필터페이지를 렌더링하도록했습니다.
   
</details>
Github: https://github.com/suldak/web-mono

#### 커뮤니티 기능을 결합한 도서 커머스 사이트 'Readme' 협업개발, 배포
<img src="https://github.com/thisisthewa2/thisisthewa2/assets/119280160/3a6df636-2691-4e28-ba6f-5beda5627109" width="300" height="200"/>

사용한 기술 스택: <img src="https://img.shields.io/badge/nextjs-000000?style=for-the-badge&logo=next.js&logoColor=white"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"> <img src="https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=white">  <img src="[https://img.shields.io/badge/axios-5a29e4?style=for-the-badge&logo=axios&logoColor=white](https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactQuery&logoColor=white)"> <img src="[https://img.shields.io/badge/reacthookform-ec5990?style=for-the-badge&logo=reacthookform&logoColor=white](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)">


<details>
<summary> 기여 </summary>

- 메인페이지: 메인페이지 ui & 자체 도서정보 api 연결
- 결제: 포트원 테스트 결제 api 연결, 주문 내역을 저장하기 위한 자체 api 연결
- 공통컴포넌트 제어: 로그인 여부 / 페이지 별 분기에 따라 컴포넌트 제어
-  CI/CD: GitHub workflow + vercel 사용

</details>
<details>
<summary> 배운점 </summary>

1. 불필요한 데이터로딩 발생: react-query의 staleTime과 gcTime 설정으로 데이터 신선도를 관리하는 법을 익혀 캐싱을 통해 성능을 최적화하였으며 enabled 옵션을 활용한 조건부 쿼리 실행으로 불필요한 데이터 로딩을 방지했습니다.
2. 주문 > 결제페이지에서 주문 내역의 일관성을 유지해야하는 문제: 전역상태관리 라이브러리인 jotai를 사용해 상품 목록과 총 결제 금액을 전역 상태로 관리하여 데이터 일관성을 유지했습니다.

</details>
Github: https://github.com/bookstore-README/front_bookstore-README

</details>




