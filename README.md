<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
    <link rel="stylesheet" href="./css/main.css" />
    <title>Seoul Dulle-gil</title>
</head>


<body>
    <br>
<span>서울 둘레길(Seoul Dulle-gil) 랜딩 페이지(홈페이지)를 만드는 예제입니다.</span>


<details-menu class="SelectMenu" role="menu">
    <div class="SelectMenu-modal rounded-3 mt-1" style="max-height:40px;">

        <div class="SelectMenu-filter">
          <input
            class="SelectMenu-input form-control js-filterable-field"
            id="toc-filter-field"
            type="text"
            autocomplete="off"
            spellcheck="false"
            autofocus
            placeholder="Filter headings"
            aria-label="Filter headings">
        </div>

      <div class="SelectMenu-list SelectMenu-list--borderless p-2" style="overscroll-behavior: contain;" data-filterable-for="toc-filter-field" data-filterable-type="substring">
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 text-emphasized" style="-webkit-box-orient: vertical; padding-left: 12px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#-starbucks"><g-emoji class="g-emoji" alias="coffee" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2615.png">☕</g-emoji> STARBUCKS</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#문자-인코딩character-encoding-설정">문자 인코딩(Character Encoding) 설정</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#뷰포트viewport-렌더링-방식-설정">뷰포트(Viewport) 렌더링 방식 설정</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#오픈-그래프the-open-graph-protocol">오픈 그래프(The Open Graph protocol)</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#트위터-카드twitter-cards">트위터 카드(Twitter Cards)</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#favicon파비콘-favorites-icon">Favicon(파비콘, favorites icon)</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 36px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#ico-파일-제작">.ico 파일 제작</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#resetcss">Reset.css</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#google-fonts">Google Fonts</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#google-material-icons">Google Material Icons</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#gsap--scrolltoplugin">GSAP &amp; ScrollToPlugin</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#swiper">Swiper</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#youtube-api">Youtube API</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#scrollmagic">ScrollMagic</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#lodash">Lodash</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#js-strict-mode">JS Strict Mode</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 36px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#엄격-모드의-장점">엄격 모드의 장점</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#랜덤한-숫자를-생성하는-함수">랜덤한 숫자를 생성하는 함수</a>
          <a role="menuitem" class="filter-item SelectMenu-item ws-normal wb-break-word line-clamp-2 py-1 " style="-webkit-box-orient: vertical; padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:325909970,&quot;originating_url&quot;:&quot;https://github.com/Parkyoungwoong/starbucks-vanilla-app&quot;,&quot;user_id&quot;:107594987}}" data-hydro-click-hmac="610ff2e5cb02430c13a0e6d84b40b53aa20fa717e2cbaf093c19174a2b1ccb75" href="#main-menu-in-header">Main menu in Header</a>
      </div>
    </div>
  </details-menu>
</details>

</body>
</html>
