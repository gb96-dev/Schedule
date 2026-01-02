# 🗓️ 일정 관리 앱 (Schedule App)

Spring Boot와 JPA를 활용하여 만든 개인 일정 관리 API 서버입니다.

## 🛠️ 개발 환경
- **Framework**: Spring Boot 3.4.1
- **Language**: Java 17
- **Database**: MySQL 8.4.7
- **ORM**: Spring Data JPA

## 🚀 구현 기능
- **일정 등록**: 제목, 내용, 담당자, 비밀번호를 입력받아 DB에 저장
- **일정 조회**: 전체 일정을 수정일 기준 내림차순(최신순)으로 조회
- **일정 삭제**: 삭제 요청 시 비밀번호를 검증하여 일치할 경우에만 삭제 처리

## 📸 테스트 완료 (Postman)
- **POST**: 일정 등록 성공 확인
- **DELETE**: ID 6번 데이터에 대해 비밀번호 "1234" 입력 시 `200 OK` 응답 및 삭제 확인 완료

  <img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/44230de4-54d1-4b38-952a-998d4775c8f7" />
