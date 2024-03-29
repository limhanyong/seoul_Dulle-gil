


## 서울 둘레길(Seoul Dulle-gil) 랜딩 페이지(홈페이지)를 만드는 예제입니다.

###### 문자 인코딩(Character Encoding) 설정
###### 문자가 인코딩되는 방식을 설정합니다.
````c
<meta charset="UTF-8"/>
````

###### UTF-8 : 초성, 중성, 종성으로 구분하여 문자를 작성(권장)
###### EUC-KR : 하나의 완성된 글자를 인식

## 뷰포트(Viewport) 렌더링 방식 설정

######  웹페이지가 화면(Viewport)에 표현되는 방식을 설정합니다.
######  모바일 환경에서 적용됩니다.

````c
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
````
+ ```` width=device-width ````: 화면의 가로 너비를 각 디바이스(Device)의 가로 너비와 동일하게 적용
+ ```` initial-scale=1.0 ````: 화면의 초기 화면 배율(확대 정도)을 설정
+ ```` user-scalable=no ````: 사용자가 디바이스 화면을 확대(yes)/축소(no)할 수 있는지 설정
+ ```` maximum-scale=1 ````: 사용자가 화면을 확대할 수 있는 최댓값
+ ```` minimum-scale=1 ````: 사용자가 화면을 축소할 수 있는 최솟값

## 오픈 그래프(The Open Graph protocol)

###### 웹페이지가 소셜 미디어(페이스북 등)로 공유될 때 우선적으로 활용되는 정보를 지정합니다.
###### Slack -

 <img src="https://github.com/limhanyong/seoul_Dulle-gil/blob/main/images/20230103_10.jpg" />

###### Kakao Talk -

 <img src="https://github.com/limhanyong/seoul_Dulle-gil/blob/main/images/20230103_11.jpg" />

###### <a href="https://ogp.me/">오픈 그래프 속성 더 보기</a>
````c
<meta property="og:type" content="website" />
<meta property="og:site_name" content="Seoul Dulle-gil" />
<meta property="og:title" content="Seoul Dulle-gil in Korea" />
<meta property="og:description" content="서울시 내 다양하게 간단한 산책로 및 산보용으로 된 둘레길이 많이 있습니다." />
<meta property="og:image" content="./images/favicon.png" />
<meta property="og:url" content="https://github.com/limhanyong/seoul_Dulle-gil" />
````

+ ```` og:type ````: 페이지의 유형(E.g, website, video.movie)
+ ```` og:site_name ````: 속한 사이트의 이름
+ ```` og:title ````: 페이지의 이름(제목)
+ ```` og:description ````: 페이지의 간단한 설명
+ ```` og:image ````: 페이지의 대표 이미지 주소(URL)
+ ```` og:url ````: 페이지 주소(URL)

## 트위터 카드(Twitter Cards)

###### 웹페이지가 소셜 미디어(트위터)로 공유될 때 우선적으로 활용되는 정보를 지정합니다.
###### <a href="https://developer.twitter.com/en/docs/twitter-for-websites/cards/guides/getting-started">더 다양한 트위터 카드 보기</a>
````c
<meta property="twitter:card" content="website" />
<meta property="twitter:site" content="Seoul Dulle-gil" />
<meta property="twitter:title" content="Seoul Dulle-gil in Korea" />
<meta property="twitter:description" content="서울시 내 다양하게 간단한 산책로 및 산보용으로 된 둘레길이 많이 있습니다." />
<meta property="twitter:image" content="./images/favicon.png" />
<meta property="twitter:url" content="https://github.com/limhanyong/seoul_Dulle-gil" />
````

+ ```` twitter:card ````: 페이지(카드)의 유형(E.g. summary, player)
+ ```` twitter:site ````: 속한 사이트의 이름
+ ```` twitter:title ````: 페이지의 이름(제목)
+ ```` twitter:description ````: 페이지의 간단한 설명
+ ```` twitter:image ````: 페이지의 대표 이미지 주소(URL)
+ ```` twitter:url ````: 페이지 주소(URL)

## Favicon(파비콘, favorites icon)

```` 
 웹페이지를 나타내는 아이콘, 웹페이지의 로고를 설정합니다.
대부분의 경우 루트 경로에 favicon.ico 파일을 위치하면 자동으로 로딩하기 때문에 <link /> 를 작성할 필요가 없습니다.
favicon.png 파일을 사용하려면 다음과 같이 <link />를 작성하세요.
````

##### 파비콘 이미지는 루트 경로에 있어야 합니다!

````c
<!--<link rel="shortcut icon" href="favicon.ico" />-->
<link rel="icon" href="./favicon.png" />
````
+ ```` favicon.ico ````: 64 x 64 (px) 또는 32 x 32 또는 16 x 16
+ ```` favicon.png ````: 120 x 120 (px), 500 x 500 (px)

 <img src="https://github.com/limhanyong/seoul_Dulle-gil/blob/main/images/favicon.ico" />
 <img src="https://github.com/limhanyong/seoul_Dulle-gil/blob/main/images/favicon.png" />

## .ico 파일 제작

##### 이지를 업로드하면 손쉽게 .ico 파일을 제작할 수 있습니다.
###### <a href="https://iconifier.net">iconifier.net</a>


## Reset.css

#####  브라우저의 기본 스타일을 초기화합니다.
````c
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
````
## Google Fonts

###### 페이지에서 사용할 '나눔고딕' 폰트를 지정합니다.

###### + 폰트 라이선스를 꼭 확인해야 합니다!

###### <a href="https://fonts.google.com">Google Fonts </a>에서 고른 폰트 파일을 가져옵니다.

````c
<link rel="preconnect" href="https://fonts.gstatic.com" />
<link href="https://fonts.googleapis.com/css2?family=Nanum+Gothic:wght@400;700&display=swap" rel="stylesheet" />
````
#### 페이지에 폰트를 적용(CSS 상속)합니다.

````c
body {
    font-family: 'Nanum Gothic', sans-serif;
}
````

## Google Material Icons

##### <a href="https://fonts.google.com/icons?selected=Material+Icons">구글에서 제공하는 머터리얼 아이콘</a> 을 무료로 사용할 수 있습니다.

##### <a href="https://m2.material.io/devlop/web/getting-started)">Getting started for web</a>

````c
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons" />
````

#### 다음과 같이 사용할 수 있습니다.

````c
<div class="material-icons">upload</div>
````

## GSAP & ScrollToPlugin

###### GSAP(The GreenSock Animation Platform)은 자바스크립트로 제어하는 타임라인 기반의 애니메이션 라이브러리입니다. ScrollToPlugin은 스크롤 애니메이션을 지원하는 GSAP 플러그인입니다.

###### 자바스크립트 지식이 뛰어나지 않아도 충분히 사용할 수 있습니다!

````c
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.5.1/gsap.min.js" integrity="sha512-IQLehpLoVS4fNzl7IfH8Iowfm5+RiMGtHykgZJl9AWMgqx0AmJ6cRWcB+GaGVtIsnC4voMfm8f2vwtY+6oPjpQ==" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.5.1/ScrollToPlugin.min.js" integrity="sha512-nTHzMQK7lwWt8nL4KF6DhwLHluv6dVq/hNnj2PBN0xMl2KaMm1PM02csx57mmToPAodHmPsipoERRNn4pG7f+Q==" crossorigin="anonymous"></script>
````
###### <a href="https://greensock.com/docs/v3/GSAP/gsap.to()">.to() 사용법 </a>
###### <a href="https://greensock.com/docs/v2/Easing">GSAP Easing</a>

````c
gsap.to(요소, 시간, 옵션)
// 또는
TweenMax.to(요소, 시간, 옵션)
````
````c
gsap.to(window, .7, {
  scrollTo: 0
});
````

## Swiper

###### <a href="https://swiperjs.com/">Swiper</a> 는 하드웨어 가속 전환과 여러 기본 동작을 갖춘 현대적인 슬라이드 라이브러리입니다.

###### <a href="https://swiperjs.com/get-started">Getting Started With Swiper</a>

###### [2021.08.26 Updated]
###### > 강의와 같이 Swiper 6버전을 사용합니다.
###### 7/8버전의 사용법이 다르기 때문에 6버전을 유지합니다.

````c
<!-- in HEAD -->
<link rel="stylesheet" href="https://unpkg.com/swiper@6.8.4/swiper-bundle.min.css" />
<script src="https://unpkg.com/swiper@6.8.4/swiper-bundle.min.js"></script>

<!-- in BODY -->
<div class="swiper-container">
  <div class="swiper-wrapper">
    <div class="swiper-slide">1</div>
    <div class="swiper-slide">2</div>
    <div class="swiper-slide">3</div>
  </div>
</div>

````

#### <a href="https://swiperjs.com/swiper-api">Swiper API</a> (옵션)을 확인하세요!

````
new Swiper(요소, 옵션);
````
````c
new Swiper('.swiper-container', {
  direction: 'vertical', // 수직 슬라이드
  autoplay: true, // 자동 재생 여부
  loop: true // 반복 재생 여부
});

````
## Youtube API

###### <a href="https://developers.google.com/youtube/iframe_api_reference?hl=ko">IFrame Player API</a> 를 통해 YouTube 동영상을 제어할 수 있습니다.

###### 유튜브 영상이 출력될 위치에 요소를 지정(생성)합니다.

````c
<!-- in HEAD -->
<script defer src="./js/youtube.js"></script>

<!-- in BODY -->
<div id="player"></div>

````
###### ```` onYouTubePlayerAPIReady ```` 함수 이름은 Youtube IFrame Player API에서 사용하는 이름이기 때문에 다르게 지정하면 동작하지 않습니다!
###### 그리고 함수는 전역(Global) 등록해야 합니다!

###### <a href="https://developers.google.com/youtube/player_parameters.html?playerVersion=HTML5&hl=ko#Parameters">플레이어 매개변수(playerVars)</a> 에서 더 많은 옵션을 확인할 수 있습니다.

````c

// Youtube IFrame API를 비동기로 로드합니다.
var tag = document.createElement('script');
tag.src = "https://www.youtube.com/iframe_api";
var firstScriptTag = document.getElementsByTagName('script')[0];
firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

function onYouTubePlayerAPIReady() {
  // <div id="player"></div>
  new YT.Player('player', {
    videoId: 'An6LvWQuj_8', // 재생할 유튜브 영상 ID
    playerVars: {
      autoplay: true, // 자동 재생 유무
      loop: true, // 반복 재생 유무
      playlist: 'An6LvWQuj_8' // 반복 재생할 유튜브 영상 ID 목록
    },
    events: {
      // 영상이 준비되었을 때,
      onReady: function (event) {
        event.target.mute(); // 음소거!
      }
    }
  });
}
````

## ScrollMagic

###### <a href="https://github.com/janpaepke/ScrollMagic">ScrollMagic</a> 은 스크롤과 요소의 상호 작용을 위한 자바스크립트 라이브러리입니다.
###### 대표적으로 어떤 요소가 현재 화면에 보이는 상태인지를 확인할 때 사용합니다.

###### <a href="http://scrollmagic.io/docs/"> ScrollMagic API</a>
````
<script src="https://cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.8/ScrollMagic.min.js"></script>
````

````c
new ScrollMagic
  .Scene({ // 감시할 장면(Scene)을 추가
    triggerElement: spyEl, // 보여짐 여부를 감시할 요소를 지정
    triggerHook: .8 // 화면의 80% 지점에서 보여짐 여부 감시
  })
  .setClassToggle(spyEl, 'show') // 요소가 화면에 보이면 show 클래스 추가
  .addTo(new ScrollMagic.Controller()) // 컨트롤러에 장면을 할당(필수!)
  
  ````
   ## Lodash
   
#### <a href="https://lodash.com/"> Lodash </a> 는 다양한 유틸리티 기능을 제공하는 자바스크립트 라이브러리입니다.

#### <a href="https://lodash.com/docs/4.17.15"> Lodash API </a>
#### <a href="https://lodash.com/docs/4.17.15#throttle"> Lodash throttle </a>

````
<script src="https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.20/lodash.min.js" integrity="sha512-90vH1Z83AJY9DmlWa8WkjkV79yfS2n2Oxhsi2dZbIv0nC4E6m5AbH8Nh156kkM7JePmqD6tcZsfad1ueoaovww==" crossorigin="anonymous"></script>
````
  
  ## JS Strict Mode
 ````
 JavaScript를 '엄격 모드'로 사용합니다.
파일 혹은 함수의 최상단에 작성해야 합니다.
````
````c
'use strict';
````
###### 'Strict Mode'는 ECMAScript 5 버전에 있는 새로운 기능으로써, 프로그램 또는 함수를 엄격한 운용 콘텍스트 안에서 실행시킬 수 있게끔 합니다. 이 엄격한 콘텍스트는 몇가지 액션들을 실행할 수 없도록 하며, 좀 더 많은 예외를 발생시킵니다.

### 엄격 모드의 장점

+ ##### 일반적인 코딩 실수에서 예외 처리
+ ##### 안전하지 않은 액션에 대한 예외 처리 (ex: 전역 객체로 접근)
+ ##### 혼란스럽거나 제대로 고려되지 않는 기능들을 비활성화

## 랜덤한 숫자를 생성하는 함수

````
// 범위 랜덤 함수(소수점 2자리까지)
function random(min, max) {
  // `.toFixed()`를 통해 반환된 문자 데이터를,
  // `parseFloat()`을 통해 소수점을 가지는 숫자 데이터로 변환
  return parseFloat((Math.random() * (max - min) + min).toFixed(2))
}
````

## Main menu in Header

````c
<ul class="main-menu">
  <li class="item">
    <div class="item__name">Seoul</div>
    <div class="item__contents">
      <div class="contents__menu">
        <ul class="inner">
          <li>
            <h4>서울 둘레길</h4>
            <ul>
              <li>둘레길 코스1</li>
              <li>둘레길 코스2</li>
              <li>둘레길 코스3</li>
            </ul>
          </li>
          ...................

````







  
  
  
  



























