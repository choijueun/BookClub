### 회원
- ID PRIMARY KEY
- 닉네임 UNIQUE
- 비밀번호
- 연락처 
- 권한 : 0승인대기 1일반회원 ~ 10admin
- 가입일 DATETIME
- 최종방문 DATETIME

### 회원아이디 백업
탈퇴해도 이미 사용된 아이디는 사용할 수 없게 함
- No PRIMARY KEY AUTO_INCREASED
- ID 

### 게시판
게시판별로 tb_board_* TABLE 생성... 전체 검색은 어떻게 하지?   
UNION ALL?   
그럼 ID는 흠
