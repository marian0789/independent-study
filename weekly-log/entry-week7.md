https://css-tricks.com/line-on-sides-headers/


 <div class="headerBar"></div>
 .headerBar {
    width: 100%;
    height: 60px;
    height: 63px;
    background-color: #383838;
    index: 2;
    z-index: 10;
    position: fixed;
    top: 0px;
}








<header class="site-header">

  <div class="menu-toggle-area">
    <button id="mobile-menu-toggle" class="button button-header mobile-menu-toggle">
      <svg class="icon-menu" width="26px" height="26px">
        <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-menu"></use>
      </svg>
    </button>
  </div>

  <div class="logo">
    <a href="/">
      <svg class="icon-logo-star" width="26px" height="26px">
        <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-logo-star"></use>
      </svg>
    </a>
  </div>

  <div class="header-middle-area">

    <a href="/" class="logo-link">
      CSS-Tricks
    </a>

  </div>

  <button id="search-opener" class="button button-header search-opener-button">
    <svg class="icon-search" width="26px" height="26px">
      <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-search"></use>
    </svg>
    <svg class="icon-close" width="26px" height="26px">
      <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-close"></use>
    </svg>
  </button>

  <div class="search" role="search" id="search-area">

    <form id="search-form" class="search-form" action="/search-results/">

      <label for="q" id="search-label" class="screen-reader">
        Search
      </label>

      <input aria-labelledby="search-label" id="q" required="" type="search" name="q" class="search-field" value="">

      <button type="submit" class="button button-header search-button">
        <svg class="icon-search" width="26px" height="26px">
          <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-search"></use>
        </svg>
      </button>

    </form>

  </div>

</header>