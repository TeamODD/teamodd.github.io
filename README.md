# TEAMODD 게임 목록 사이트

## 게임 추가 방법

1. https://teamodd.pages.dev/admin으로 접속
2. 로그인 창이 나온다.
3. 팀오드 구글 계정(이메일, 비번)을 치고 로그인
4. 게임을 추가, 삭제 할 수 있는 관리자 페이지가 나온다.

---

### placeholder만들기

placeholder란?\
-> 이미지, 텍스트 같은거 로딩중일때 임시로 채워넣는 거. 여기서는 게임 썸네일 로딩시에 채워넣는 블러 처리한 썸네일을 사용\
없어도 문제는 안생기지만 있으면 좋음

만드는법

1. https://blurha.sh/ << 접속
2. 밑으로 내리면 파란색 업로드 버튼 있음. 썸네일 이미지 업로드.
3. 업로드 하면 중간에 `LEHV6nWB...` << 이런 이상한 거 나옴.
4. 복사 후 `"placeholder": "여기다 붙여넣기"`
