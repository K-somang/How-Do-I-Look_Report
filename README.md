# 개인 개발 리포트

#### 작성자 : 유소망
#### 팀명 : 2팀
#### 프로젝트명 : How-Do-I-Look
#### 프로젝트 기간 : 2025년 6월 26일 ~ 2025년 7월 15일
#### 개인 개발 리포트 작성일 : 2025년 7월 13일

## 1. 프로젝트 개요
#### 스타일 공유 및 큐레이팅 서비스를 제공하는 "How-Do-I-Look" 입니다. 
#### 누구든지 나만의 스타일을 자유롭게 공유하고 큐레이터들에게 평가를 받아 소통하는 기능을 제공하는 서비스입니다. 
#### 다양한 이용자들이 패션에 대한 생각을 나누고 소통할 수 있는 공간을 제공합니다.

## 2. 기술 스택 및 협업 도구

| 분류       | 사용 예정 도구                                  |
|------------|-----------------------------------------------|
| Backend    | Node.js (Express)                             |
| Database   | PostgreSQL                                    |
| API 문서화 | Notion                                        |
| 협업 도구  | Discord, GitHub, Notion                       |
| 일정 관리  | GitHub Issues + Notion 타임라인               |
| npm list   | prisma, express, morgan, multer, cors, superstruct, nodemon, dotenv |
| 배포       | Render    

## 3. 담당 작업
### (1) 답글 API 구현
#### 큐레이팅 항목에 입력되는 답글의 등록, 수정, 삭제 API를 구현했습니다.

### (2) 비밀번호 해싱 처리
#### 비밀번호 입력 시 단방향 암호화 하였으며, 인증 시 이를 비교하는 로직을 구현했습니다.

## 4. 기술적 성과
### (1) 답글 등록, 수정, 삭제 API 구현
#### commentRoute.js : 각 기능별 API 엔드포인트 구성 및 유효성검사 적용
![](https://github.com/K-somang/image_upload_repository/blob/main/commentRoute.png)

#### commentControllers.js : 클라이언트의 요청을 받고 서비스 코드를 호출하여 응답을 처리

#### commentService.js : 컨트롤러의 요청에 따라 DB 접근 및 비즈니스 로직 구현


## 5. 문제점 및 해결 과정



## 6. 향후 개선 사항 및 제안
