> 회원

- id		PK & FK
- nickname	UNIQUE
- password	VARCHAR(25)
- url		VARCHAR(100)
- reg_date		DATETIME
- pw_modify_date	DATETIME

> 회원ID

- 탈퇴해도 이미 사용된 아이디는 사용할 수 없게
- No		PK & AUTO INCREASED
- id		UNIQUE
