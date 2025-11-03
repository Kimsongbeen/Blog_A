# Blog_A
Node.js와 Express를 사용해 만든 간단한 블로그 API 프로젝트로 신입 백엔드 개발자가 CRUD 기능과 배포 경험을 쌓기 위해 만든 미니 프로젝트입니다.

### 기술 스택
- Backend: Node.js, Express
- Database: SQLite (개발용) / PostgreSQL (배포용)
- Deployment: Render (무료 플랜)
- 기타: Postman, dotenv, CORS

### 주요 기능
- 게시글 CRUD
  - GET /posts : 게시글 목록 조회
  - GET /posts/:id : 게시글 상세 조회
  - POST /posts : 게시글 작성
  - PUT /posts/:id : 게시글 수정
  - DELETE /posts/:id : 게시글 삭제
- 간단한 인증(Optional)
