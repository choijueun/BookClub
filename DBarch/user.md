### 회원ID
탈퇴해도 이미 사용된 아이디는 사용할 수 없게
1. No
    - PK & AUTO_INCREASED
1. id		
    - UNIQUE

<br/>

### 회원
1. id		
    - PK & FK
1. nickname	
    - UNIQUE
1. password	
    - VARCHAR(25)
1. url (NULL)
    - VARCHAR(100)
1. reg_date		
    - DATETIME
1. pw_modify_date	
    - DATETIME

<br/>

### 로그인 내역
1. id
    - PK & AUTO_INCREASED
1. Login
    - DATETIME
