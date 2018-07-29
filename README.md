# enlightenment
We see as much as we Know

2018-07-24 It starts from now.

I want to see her.

2018-07-26 jumbotron, KondratievCycles

why didn't it?

please..

2018-07-26 navbar

1조 : Drone Picnic
학건 승호 유진 화용 지원
API 크롤링
DB 테이블 널 허용 여부 체크해볼 것
폴리곤

2조 : JAM 단체 플래너
태혁 한상 유진 재영 경우
Github 형상관리
여행 일정 좋아요 공유 기능

3조 : ALDALDAL 
준철 상완 홍기 원빈
방문자 유입량 데이터 시각화 연동

4조 : NAONNA
은석 찬준 도우 도현
특정 거리 이내 자동 매칭 시스템
소셜 계정 연동 로그인

5조 : 코코딩딩
준성 석희 정현 태욱
문제풀이실력(소비정도)에 따른 레벨화(등급) - 군집분석가능
고객에게 목표달성을 유도하는 시각화 구현

2018-07-30

<body></body> 태그 뒤에
--
<script>
  window.kakaoAsyncInit = function () {
    Kakao.Story.createFollowButton({
      container: '#kakaostory-follow-button'
    });
  };

  (function (d, s, id) {
    var js, fjs = d.getElementsByTagName(s)[0];
    if (d.getElementById(id)) return;
    js = d.createElement(s); js.id = id;
    js.src = "//developers.kakao.com/sdk/js/kakao.story.min.js";
    fjs.parentNode.insertBefore(js, fjs);
  }(document, 'script', 'kakao-js-sdk'));
</script>
--

스토리 소식받기 버튼을 표시할 위치에 아래 코드 삽입
--
<div id="kakaostory-follow-button" data-id="healthenjoy" data-type="vertical" data-show-follower-count="true"></div>
--