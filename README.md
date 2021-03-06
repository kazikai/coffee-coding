# coffee-coding
---
목적 : 가볍게 커피마시면서 코딩하고 서로의 프로젝트를 공유하는 모임

---
 ## 본문서는 마크다운으로 작성 되었습니다.
---


#참여멤버: 총8명
- 김성원
- 이현국
- 윤정현
- 윤정민
- 배철민
- 서자랑
- 신호철
- 한정현

# Ground Rule
* 모이는 시간은 매주 화요일 6시 밥 먹고 2층
* 6시 30분 2층
* 모여서 1시간 공유 이후 1시간 코딩 ( 원하는 사람만  )
* 1달에 한번은 외부에 나가자
* 모임은 누가 주도할 것인지? 순서대로 돌아가면서.
*

# 모임 순서
* 이현국 (3/29)
* 윤정현 (4/5)
* 윤정민 (4/12) - 2층!
* 배철민 (4/19) - 판교 파스쿠치
* 서자랑 (4/26)
* 신호철 (5/3)
* 서자랑 (5/31)

# 주간모임공유
* [20160426](https://github.com/kazikai/coffee-coding/blob/master/weekly/2016.04.26.md)
* [20160503](https://github.com/kazikai/coffee-coding/blob/master/weekly/2016.05.03.md)
* [20160531](https://github.com/kazikai/coffee-coding/blob/master/weekly/2016.05.31.md)
* [20160628](https://github.com/kazikai/coffee-coding/blob/master/weekly/2016.06.28.md)

#프로젝트설명 (양식은 자유)
한정현 :
* 알뜰 구매 Bot : 1달 정도 ( 4/26 까지 ) - 사실상 개발및 운영은 완료..
  * telegram bot 개발하기: [hotdeal_bot](https://github.com/kazikai/coffee-coding/blob/master/hotdeal_bot.md)
  * 클리앙 알뜰구매 관련 노티 @Hotdeal_bot
  * node.js로 개발 : wrapper는 현재 사용하지 않을 계획이나, 구현이슈로 사용할 수도있음
  * 현재 node.js 로 chat_id 받아와서 텔레그램으로 전송하는 부분 개발 완료
  * 다음주는 거의 완성된 telegram 봇을 공유할 예정
  * 작성 완료 ( 4/15 )
  * 현재사용자 300여명 ( 방문자는 600여명 )
    * 클리앙 팁과 강좌 게시판에 공유 이후
* 파이썬 django 관련 정리
  * 5월 모임부터. 공유 예정
* jsweekly Bot 개발
  * 이건 최대한 빨리
* 미세먼지 알림 Bot
  * 요즘 만들어서 공유하면 좋을것 같은데.. api를 어디서 가져올지 안정해짐
  * 2차로 미세먼지 봇 개발
  * 그다음 일정관리app  개발
* 주식 알림 Bot ( 미정 )
  * 원하는 종목 상한/하한 알림
  * 원하는 종목 조회
  * 원하는 종목 장 열린후, 점심, 장 종료후 알림



신호철 :
* 부동산봇 : http://dsp.fun25.co.kr/wiki/index.php/%EB%B6%80%EB%8F%99%EC%82%B0_%EB%B4%87

윤정현 :
* 목적 - 자체 쇼핑몰 홈페이지 template 및 자체 위젯 확보
  * 시중에 판매되는 쇼핑몰 홈페이지 template 구입
  * 내부 html, js, css코드 분석 및 성능 개선
  * 필요한 모듈을 위젯 형식으로 관리
  * 반응형 웹에 대한 연구
  * ( 텔레그램 봇 개발도 굉장히 매력적이네요 어느정도 마무리되면 저도 도전해보려합니다 :) )


윤정민 :
* iOS용 필터카메라 앱 개발
  * Swift로 개발
  * GPUImage framework (https://github.com/BradLarson/GPUImage) 사용
  * Custom filter 개발을 위한 OpenGL ES Shader 공부 (https://www.raywenderlich.com/70208/opengl-es-pixel-shaders-tutorial 등)


김성원 : (2016.04.19v)
* 범용 키워드 알림 BOT
  * URL과 Keyword를 입력하면 해당 URL에 Keyword가 보일 시 Noti
  * 알림채널
    * Slack bot (x)
    * Telegram bot (-ing)
    * Email (x)
    * SMS (x)
  * 1차구현
    * CGV 영화페이지 [상영시간표](http://www.cgv.co.kr/reserve/show-times/?areacode=01&theaterCode=0074&date=20160402)를 이용한 예매풀림 알림
    * my-secretary.heroku.com 에서 지금까지 등록된 URL&Keyword 확인 가능
    * Telegram bot api 연동 완료 (@KeywordNotiBot)

이현국 :
* Pizle 업데이트
  * 2013년 제작한 Pizle 앱을 업데이트 하는 목적
  * 여러가지 기능 추가
  * 국내에서 성공 후 세계적인 서비스로 만들기

서자랑 :
* 개인 블로그형 웹페이지 제작하기
* 목적 : 마크업부터 JS, deploy까지 전부 경험을 목적
* TODO :
  * 웹 서버 구매
  * 노트북 구매(ㅎㅎ)
  * 도메인 구매

배철민 :
* 업데이트가 늦었습니다.
* 주제 : 아두이노를 활용한 RC카 개발
* 목적 : 스크래치X를 활용한 RC카 개발을 통해 IOT 초급수준의 기량 습득, 좀 더 꾸준히 한다면 라즈베리파이+nodejs 를 활용한 드론개발까지
* RC카 구상 :
      * 하드웨어 : 타미야 Amphibious vehicle kit
      * 기판 : 아두이노 우노
      * 소프트웨어 : 스크래치 X
* 관련 기술 :
      * 아두이노
      * 스크래치X
      * iOS(remote control 용)
* TODO :
  * 아두이노 학습 : http://opensource.kofac.re.kr/index.do 활용
  * 회로도 구성
  * 하드웨어 조립
  * 회로도 구성
  * 하드웨어용 소프트웨어 개발
  * remote control용 iOS 소프트웨어 개발 (swift 기반)
  * 완료
