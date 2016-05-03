#telegram bot


# webhook 구현 완료
* https://api.kazikai.net:8443/<token>
    * POST
* 파라미터 : webhook api
* 포트는 3000, 8443 2개 ( )
* 3000(http), 8443(https)


# 제작한 api
* 유저 등록
* 노티 유저 등록
* 유저 삭제
* 노티 유저 삭제
* 전체 노티유저한테 메시지 보내기
* 클리앙 알뜰구매 조회 API (1분마다 crontab 호출 )
* 관리자 api ( 전체 유저, 노티 유저 리턴 )

# 문제 해결
*  block 한 유저는 어떻게 처리할것인가?
    * sendMessage 를 한후에 return값을 보고 HTTP response 가 403 이면
    * 해당 유저는 noti 에서 제외 시킨다.
* 클리앙 페이지의 임시조치 및 url을 제대로 가져오지 못할때
    * 오류 핸들링 처리
* 키값 분리
    * 키관련 코드와 로직 코드는 서로 분리
    * 로직 코드는 github 또는 bitbucket 에 올릴 예정

