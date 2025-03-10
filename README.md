# Java Study

- 자바 ?
- DB
- CRUD 게시판 생성해보기 

## java day

## 202502-03
- 개발환경 셋팅 
- 자바의 정석 / 기본

## 20250214
- mac / jdk21 / eclipse / springboot 설치

## 20250215
- springboot 설치성공 / HelloWorld 까지 출력해보기

## 20250216 
#개발환경 
1. IDE : eclipse 
2. spring Boot 4 
3. Jdk 21
4. mysql
5. Spring Data JPA
6. Thymleaf 

#게시판 주요기능 
1. 글쓰기(board/save)
2. 글목록(board/)
3. 글조회(board/{id})
4. 글수정(board/update/{id})
5. 글삭제 (board/delete/{id})
5. 페이징처리(board/paging)

# Spring Boot + React 게시판 개발 로드맵
1️⃣ 프로젝트 기획 및 환경 설정
기능 정의 (게시글 CRUD, 로그인, 댓글, 페이징 등)
ERD 설계 (사용자 테이블, 게시글 테이블, 댓글 테이블 등)
개발 환경 구성 (Eclipse + JDK 21 + Spring Boot 4 + MySQL + React)
GitHub 저장소 생성 및 초기 세팅

2️⃣ 백엔드 개발 (Spring Boot 4 & JPA)
프로젝트 구조 설계 (Layered Architecture 또는 Hexagonal Architecture)
MySQL과 연동 (Spring Data JPA 사용)
엔티티 및 레포지토리 생성
서비스 및 비즈니스 로직 구현
REST API 개발 (게시글 CRUD, 페이징, 댓글 기능 추가)
Spring Security 또는 JWT로 인증 및 인가 적용


3️⃣ 프론트엔드 개발 (React)
React 프로젝트 생성 및 구조 설계
Axios를 이용한 API 연동
게시판 UI 구성 (Material UI 또는 Tailwind CSS 사용 가능)
CRUD 기능 구현
React Router를 이용한 페이지 네비게이션
상태 관리 (useState, useReducer 또는 Redux)

4️⃣ 연동 및 테스트
CORS 설정 및 API 연결 확인
React와 Spring Boot 연동
기본적인 유닛 테스트 및 통합 테스트
오류 및 예외 처리

5️⃣ 배포 및 유지보수
Docker 및 CI/CD 적용
AWS 또는 Vercel, Netlify 등에 배포
프로젝트 문서화 및 유지보수 계획 수립


  
