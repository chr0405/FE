# 🍀Friend
![main](https://github.com/chr0405/js_counter/assets/129362281/022d3f4f-20e6-43eb-817e-09cb90a47ee1)
당신의 'FRIEND'를 만나보세요!\
지인 매칭 100% 방지와 개인정보 노출 부담 없는 교내 매칭 서비스

## 💚Friend란?

안녕하세요! Friend를 소개합니다!\
Friend를 한 마디로 소개하자면 "지인 매칭 100% 방지와 개인 정보 노출 부담 없는 교내 매칭 서비스"입니다\
100% 실제 사람이 매칭해주어 당신의 특별한 Friend를 찾도록 도와주는 프리미엄 교내 소개팅 매칭 서비스입니다

## 💚Demo

Web site : [Demo](https://dev--rococo-dragon-c69f42.netlify.app)\
youtube : [시연 연상](https://www.youtube.com/watch?v=jvkPfVLO6fc)

## 🧪개발 기간

2023.12.31 ~ 2024.02.19

## 👽개발자

* **PM**\
  유디 / 양준혁
  
* **디자이너**\
  제노니스 / 박성연
  
* **Front-end**\
**팀장** 이매 / 조하림\
다니 / 김예진\
린주 / 노준일\
도율 / 정현진

* **Back-end**\
**팀장** 난초 / 최민석\
크리스 / 채정훈\
베리 / 배재영\
호야 / 이준호

## 📗Front-end 회의록
<a href="https://bottlenose-barberry-5ba.notion.site/Friend-FE-489356d3cfff48a5ad3682515a3e5a7f?pvs=4"><img src="https://img.shields.io/badge/notion-000000.svg?&style=for-the-badge&logo=notion&logoColor=white"/></a>

## 🧩Front-end 기술 스택
<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white" style="margin-right: 10px;"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" style="margin-right: 10px;"/>
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white" style="margin-right: 10px;"/>
  <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" style="margin-right: 10px;"/>
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white"/>
</p>

## 📚파일 구조
```
📁src
  ├── 📁components
  │   ├── 📁Board  # 게시판 보드
  │   │   ├──ManagerNoticeBoard.jsx  # 공지사항 (관리자 페이지)에 쓰이는 Board
  │   │   ├──ManagerQnABoard.jsx  # Q&A 모아보기 (관리자 페이지)에 쓰이는 Board
  │   │   ├──ManagerRBD.jsx  # 비매너 유저 신고하기 - 더 자세한 신고 내용 입력에 쓰이는 Board
  │   │   ├──ManagerReportBoard.jsx  # 관리자 페이지 - 신고 접수 내역 모아보기에 쓰이는 Board
  │   │   ├──ManagerReviewBoard.jsx  # 관리자 페이지 - 솔직후기에 쓰이는 Board
  │   │   ├──MatchingHistoryBoard.jsx  # 매칭 내역에 쓰이는 Board
  │   │   ├──NoticeBoard.jsx  # 공지사항에 쓰이는 Board
  │   │   ├──QnABoard.jsx  # Q&A (이용자가 헤더에서 접근하는 경우)에 쓰이는 Board
  │   │   ├──ReviewBoard.jsx  # 솔직후기 - 자세히에 쓰이는 Board
  │   │   └──ReviewDetailBoard.jsx  # 솔직후기에 쓰이는 Board
  │   ├── 📁CircleCheckbox
  │   │   └──CircleCheckbox.jsx  # 매칭 신청에 쓰이는 체크란
  │   ├── 📁footer
  │   │   └──index.jsx  # 푸터
  │   ├── 📁header
  │   │   └──index.jsx  # 헤더
  │   ├── 📁ImageBox
  │   │   └──index.jsx  # 메인 페이지에 쓰이는 Image Box Component
  │   ├── 📁JudgePage
  │   │   └──JudgePage.jsx  # 마이페이지 - 심사 중 페이지
  │   ├── 📁LimitInputForm
  │   │   └──LimitInputForm.jsx  # 회원가입 - 3에 쓰이는 110자 제한 textarea Component
  │   ├── 📁ManagerPage_Component  # 관리자 페이지에서 방문할 수 있는 사이트
  │   │   ├──ManagerNotice.jsx  # 공지사항
  │   │   ├──ManagerPage.jsx  # 관리자 페이지 홈
  │   │   ├──ManagerReview.jsx  # 관리자 페이지 - 솔직후기
  │   │   ├──ManagerReviewDetail.jsx  # 관리자 페이지 솔직후기 - 자세히
  │   │   ├──MatchingAHDetailMan.jsx  # 관리자 페이지 - 매칭 신청 내역 보기 - 남자
  │   │   ├──MatchingAHDetailWoman.jsx  # 관리자 페이지 - 매칭 신청 내역 보기 - 여자
  │   │   ├──MatchingApplicationHistoryMan.jsx  # 매칭 신청 내역 - 남자
  │   │   ├──MatchingApplicationHistoryWoman.jsx  # 매칭 신청 내역 - 여자
  │   │   ├──MatchingCompletionHistory.jsx  # 매칭 완료 내역
  │   │   ├──QnA.jsx  # 관리자 페이지 - Q&A 모아보기
  │   │   ├──qnaDetail.jsx  # 관리자 페이지 - Q&A 모아보기 - Q&A 자세히
  │   │   ├──qnaResponse.jsx  # 관리자 페이지 - Q&A 답변하기
  │   │   ├──ReportReceiptHistory.jsx  # 관리자 페이지 - 신고 접수 내역 보기
  │   │   ├──ReportReceiptHistoryDetail.jsx  # 관리자 페이지 - 신고 접수 내역 보기 - 자세히
  │   │   ├──ViewMembershipDetail.jsx  # 관리자 페이지 - 회원 목록 보기 - 자세히
  │   │   ├──ViewMembershipList.jsx  # 관리자 페이지 - 회원 목록 보기
  │   │   └──WritingNotices.jsx  # 관리자 페이지 - 공지사항 쓰러가기
  │   ├── 📁MyPage_Component  # 마이페이지에서 방문할 수 있는 사이트
  │   │   ├──DeactivateAccount.jsx  # 계정 비활성화
  │   │   ├──MatchingHistory.jsx  # 매칭 내역
  │   │   ├──MembershipWithdrawal.jsx  # 회원 탈퇴
  │   │   ├──ModifyingInfo.jsx  # 회원 정보 수정
  │   │   ├──MyPage.jsx  # 마이페이지
  │   │   ├──NonMannerUsers.jsx  # 비매너 유저 신고하기
  │   │   └──ProfileCard.jsx  # 프로필 카드
  │   ├── 📁PersonBlock  # 회원 블록
  │   │   ├──JoinPersonBlock.jsx  # 회원 가입 신청 내역 모아보기 등에 필요한 회원 블록
  │   │   ├──MatchingPersonBlock.jsx  # 매칭 신청 내역 모아보기에 필요한 회원 블록
  │   │   └──MemberPersonBlock.jsx  # 회원 목록 보기에 필요한 회원 블록
  │   ├── 📁title
  │   │   └──index.jsx  # 타이틀
  ├── 📁images  # 이미지 파일 저장 디렉토리
  ├── 📁pages
  │   ├── 📁ApplicationForMembership  # 관리자 페이지 - 회원 가입 신청
  │   │   ├──ApplicationForMembership.jsx  # 관리자 페이지 - 회원 가입 신청 내역 보기
  │   │   └──ApplicationForMembershipDetail.jsx  # 관리자 페이지 - 회원 가입 신청 내용 자세히 보기
  │   ├── 📁Certify   # 회원가입
  │   │   ├──CertifyBeginning.jsx  # 회원가입
  │   │   ├──CertifyEmail.jsx  # 부경대 학생 인증 - 1
  │   │   └──CertifyEnd.jsx  # 부경대 학생 인증 - 2
  │   ├── 📁FindAccount   # 계정 찾기
  │   │   ├──FindID.jsx  # 아이디 찾기
  │   │   └──FindPassword.jsx  # 비밀번호 찾기
  │   ├── 📁Login   
  │   │   └──Login.jsx  # 로그인
  │   ├── 📁Main  
  │   │   └──MainPage.jsx  # 메인 페이지
  │   ├── 📁MatchApply  
  │   │   └──Apply.jsx  # 매칭 신청, 매칭 신청 완료 팝업
  │   ├── 📁Notice   # 공지사항
  │   │   ├──DeleteModal.jsx  # (관리자용) 공지사항 삭제 모달
  │   │   ├──ManagerNoticeDetail.jsx  # (관리자용) 공지사항 - 자세히
  │   │   ├──ModifyModal.jsx  # (관리자용) 공지사항 수정 모달
  │   │   ├──ModifyNotice.jsx  # (관리자용) 공지사항 수정 페이지
  │   │   ├──notice.jsx  # 공지사항 페이지
  │   │   └──NoticeDetail.jsx  # (이용자용) 공지사항 - 자세히
  │   ├── 📁QnA   
  │   │   ├──qna.jsx  # Q&A (이용자가 헤더에서 접근)
  │   │   ├──qnaDetail.jsx  # Q&A - 자세히
  │   │   └──qnaWrite.jsx  # Q&A - 글 작성 (이용자가 질문 남기는 경우)
  │   ├── 📁Report   
  │   │   └──report.jsx  # 비매너 유저 신고하기 - 더 자세한 신고 내용 입력
  │   ├── 📁Review
  │   │   ├──review.jsx  # 솔직후기
  │   │   ├──ReviewDetail.jsx  # 솔직후기 - 자세히
  │   │   └──write.jsx  # 솔직후기 작성
  │   └── 📁Signup
  │   │   ├──ProfileImage.jsx  # 회원가입 - 3 프로필 이미지 삽입
  │   │   ├──SignupInfo.jsx  # 회원가입 - 1 양식 작성
  │   │   └──SignupTerms.jsx  # 회원가입 - 2 동의서
  ├── 📁REDUX
  │   ├── emailCheck.js  # 이메일 정보 저장
  │   ├── loginCheck.js  # 로그인 정보 저장
  │   ├── matchingCheck.js  # 매칭 정보 저장
  │   └── store.js
  ├── 📁styles
  │   └── font.css  # 기본 폰트 설정
  └── App.tsx  # 메인 App 컴포넌트
```
