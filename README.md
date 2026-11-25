## 안녕하세요, 백엔드 개발자 정민재입니다

만든 기능은 직접 호출해 보고, 응답만이 아니라 DB에 남은 값까지 확인하면서 개발합니다.
Java · Spring Boot로 팀 프로젝트 세 개를 진행하며 회원 인증, 쇼핑몰 관리자 기능, 식단 기록과 보상 시스템을 맡았습니다.

- 📧 vovodla74@gmail.com

<br>

### 🛠 Tech

| 분야 | 기술 |
|---|---|
| Backend | Java, Spring Boot, Spring Security, JPA, QueryDSL |
| Database | MySQL, Oracle, Redis |
| Frontend | React, Zustand, Axios, Thymeleaf, jQuery |
| Tools | Docker Compose, Git/GitHub, IntelliJ |

<br>

### 📂 Projects

#### 🥗 [밀스루틴 (MealthRoutine)](https://github.com/sangsoo-L/MealthRoutine) · 2026.11 · 6인 팀
운동 초보를 위한 운동·식단 헬스케어 웹 · **식단 기록과 보상 시스템 백엔드 담당**
- 음식 검색·식단 기록·식단 목표·출석·오늘의 퀴즈·보상 API 19개
- 식단 60 + 미션 40 하루 점수를 다음 날 00:05에 한 번만 확정해 경험치·포인트 지급
- 같은 날 포인트가 두 번 들어간 버그를 지급 키 + DB UNIQUE 제약으로 차단
- 식약처 식품영양성분 공공데이터 23,442건 적재, 점수 계산 JUnit 단위 테스트
- 직접 만든 API를 React 화면에 연결하고, 코드 리뷰를 반영해 섭취량 단위·자정 경계 처리 보완

`Spring Boot 4` `JPA` `MySQL` `Docker` · 👉 **[자세히 보기](projects/mealthroutine.md)**

#### ✈️ [TripFinder](https://github.com/Minjae1357/TripFinder) · 2026.08 ~ 09 · 3인 팀
여행 추천 커뮤니티 · **로그인·보안·게시판 담당** ([프론트엔드](https://github.com/Minjae1357/React-TripFinder))
- Spring Security + JWT 로그인, Refresh Token은 HttpOnly 쿠키로 발급
- 이메일 인증 회원가입(6자리 코드를 Redis에 5분 저장), 카카오·구글·네이버 소셜 로그인
- 게시판(대댓글·좋아요·이미지 업로드·작성자/관리자 권한)과 React 로그인·게시판 화면

`Spring Boot` `Spring Security` `JPA` `MySQL` `Redis` `React`

#### 🛒 [Ezmarket](https://github.com/Minjae1357/Ezmarket) · 2024.03 ~ 05 · 2인 팀 (3인으로 시작)
온라인 쇼핑몰 · **회원·관리자·장바구니 담당**
- Spring Security 폼 로그인, 구글 로그인·회원가입, 이메일 인증
- 관리자: 상품 등록(색상·브랜드·이미지 여러 장), 회원 활성/비활성, 배송 상태 변경
- 중간에 빠진 팀원의 장바구니·주문 파트를 이어받아 마무리

`Spring Boot` `Spring Security` `JPA` `QueryDSL` `Oracle` `Thymeleaf`
