# Millie Backend

Spring Boot 기반의 도서 관리 백엔드 서비스입니다.

## 기술 스택

- Java
- Spring Boot
- JPA/Hibernate
- Maven
- H2 Database

## 주요 기능

- 사용자 관리 (User Management)
- 도서 관리 (Book Management)
- 좋아요 기능 (Like System)

## API 엔드포인트

### User Controller
- 사용자 등록, 조회, 수정, 삭제
- 로그인 기능

### Book Controller
- 도서 목록 조회
- 도서 상세 정보 조회

### Like Controller
- 도서 좋아요/좋아요 취소
- 사용자별 좋아요 목록 조회

## 실행 방법

```bash
# Maven을 사용하여 실행
./mvnw spring-boot:run

# 또는 Docker를 사용하여 실행
docker-compose up
```

## 데이터베이스

H2 인메모리 데이터베이스를 사용하며, `data.sql` 파일을 통해 초기 데이터가 로드됩니다.
