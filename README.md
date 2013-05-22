mamoi
=====
<!DOCTYPE html>
<!--
  Theme: Tokusetsu
  by @sanographix
  http://www.sanographix.net
  (c) 2013 Showkaku Sano [sanographix@gmail.com]
  Free to use under the MIT license.
  Please leave at least ONE credit link. Do not delete this box.
-->

<html lang="ja" prefix="og: http://ogp.me/ns# fb: http://www.facebook.com/2008/fbml">
<head>

  <!-- Variables -->
  <meta name="text:Google Analytics ID" content="" />
  <meta name="text:Introduction" content="" />
  <meta name="text:Introduction Heading" content="Introduction" />
  <meta name="text:Youtube Embed Code" content="" />
  <meta name="text:Soundcloud Embed Code" content="" />
  <meta name="text:Nicovideo Embed Code" content="" />
  <meta name="text:Footer Text" content="" />

  <meta name="text:Circle Name" content="" />
  <meta name="text:Circle URL" content="" />
  <meta name="text:Spec" content="" />
  <meta name="text:Release Date" content="" />
  <meta name="text:Event Space Number" content="" />
  <meta name="text:Price" content="" />

  <meta name="text:Store01 Name" content="" />
  <meta name="text:Store01 URL" content="" />
  <meta name="text:Store02 Name" content="" />
  <meta name="text:Store02 URL" content="" />
  <meta name="text:Store03 Name" content="" />
  <meta name="text:Store03 URL" content="" />
  <meta name="text:Store04 Name" content="" />
  <meta name="text:Store04 URL" content="" />

  <meta name="text:Track01 Title" content="" />
  <meta name="text:Track01 Description" content="" />
  <meta name="text:Track02 Title" content="" />
  <meta name="text:Track02 Description" content="" />
  <meta name="text:Track03 Title" content="" />
  <meta name="text:Track03 Description" content="" />
  <meta name="text:Track04 Title" content="" />
  <meta name="text:Track04 Description" content="" />
  <meta name="text:Track05 Title" content="" />
  <meta name="text:Track05 Description" content="" />
  <meta name="text:Track06 Title" content="" />
  <meta name="text:Track06 Description" content="" />
  <meta name="text:Track07 Title" content="" />
  <meta name="text:Track07 Description" content="" />
  <meta name="text:Track08 Title" content="" />
  <meta name="text:Track08 Description" content="" />
  <meta name="text:Track09 Title" content="" />
  <meta name="text:Track09 Description" content="" />
  <meta name="text:Track10 Title" content="" />
  <meta name="text:Track10 Description" content="" />

  <meta name="text:Staff01 Name" content="" />
  <meta name="text:Staff01 Role" content="" />
  <meta name="text:Staff01 URL" content="" />
  <meta name="text:Staff02 Name" content="" />
  <meta name="text:Staff02 Role" content="" />
  <meta name="text:Staff02 URL" content="" />
  <meta name="text:Staff03 Name" content="" />
  <meta name="text:Staff03 Role" content="" />
  <meta name="text:Staff03 URL" content="" />
  <meta name="text:Staff04 Name" content="" />
  <meta name="text:Staff04 Role" content="" />
  <meta name="text:Staff04 URL" content="" />
  <meta name="text:Staff05 Name" content="" />
  <meta name="text:Staff05 Role" content="" />
  <meta name="text:Staff05 URL" content="" />
  <meta name="text:Staff06 Name" content="" />
  <meta name="text:Staff06 Role" content="" />
  <meta name="text:Staff06 URL" content="" />
  <meta name="text:Staff07 Name" content="" />
  <meta name="text:Staff07 Role" content="" />
  <meta name="text:Staff07 URL" content="" />
  <meta name="text:Staff08 Name" content="" />
  <meta name="text:Staff08 Role" content="" />
  <meta name="text:Staff08 URL" content="" />
  <meta name="text:Staff09 Name" content="" />
  <meta name="text:Staff09 Role" content="" />
  <meta name="text:Staff09 URL" content="" />
  <meta name="text:Staff10 Name" content="" />
  <meta name="text:Staff10 Role" content="" />
  <meta name="text:Staff10 URL" content="" />

  <meta name="if:Dark Theme" content="0"/>
  <meta name="if:Enable Facebook Button" content="1"/>
  <meta name="if:Enable Tweet Button" content="1"/>
  <meta name="if:Enable Bookmark Button" content="1"/>
  <meta name="if:Enable Plus1 Button" content="1"/>

  <meta name="image:Main Image" content="http://static.tumblr.com/131a45f66a50ec2a0fd3417386257c7e/xlsgtjb/H4Amhy1rn/tumblr_static_header-noimage.gif"/>
  <meta name="image:Jacket" content=""/>
  <meta name="image:Banner1" content=""/>
  <meta name="image:Banner2" content=""/>
  <meta name="image:Background" content=""/>
  <meta name="font:Font" content="'Open Sans', 'Helvetica', 'Arial', 'Hiragino Kaku Gothic Pro', Meiryo, 'MS PGothic', sans-serif"/>
  <!-- END Variables -->

  <meta charset="utf-8">
  <title>{block:PostTitle}{PostTitle} - {/block:PostTitle}{Title}</title>
  {block:Description}
  <meta name="description" content="{MetaDescription}" />
  {/block:Description}
  <meta name="viewport" content="width=device-width">

  <meta property="og:title" content="{block:PostTitle}{PostTitle} - {/block:PostTitle}{Title}" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="{Permalink}" />
  <meta property="og:image" content="{block:IfJacketImage}{image:Jacket}{/block:IfJacketImage}{block:IfNotJacketImage}{PortraitURL-128}{/block:IfNotJacketImage}" />
  <meta property="og:site_name" content="{Title}" />
  <meta property="og:description" content="{block:Description}{MetaDescription}{/block:Description}">

  <link rel="stylesheet" media="screen" href="http://sanographix.github.com/public/tumblr/tokusetsu/css/style.css" />
  <link rel="shortcut icon" href="{Favicon}">
  <link rel="apple-touch-icon" href="{PortraitURL-128}">

  <!--[if IE]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.6.1/html5shiv.js"></script>
    <link rel="stylesheet" media="screen" href="//sanographix.github.com/public/tumblr/tokusetsu/css/fuck-ie.css" />
  <![endif]-->

  <!--[if lte IE 7]>
    <link rel="stylesheet" media="screen" href="//sanographix.github.com/public/tumblr/tokusetsu/css/font-awesome-ie7.css" />
  <![endif]-->

  <!-- Google Analytics -->
  <script type="text/javascript">
    var _gaq = _gaq || [];
    _gaq.push(['_setAccount', '{text:Google Analytics ID}']);
    _gaq.push(['_trackPageview']);
    (function() {
      var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
      ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
      var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
    })();
  </script>
  <!-- END Google Analytics -->

</head>
<body class="{block:IndexPage}page-index{/block:IndexPage}
             {block:PermalinkPage}page-permalink{/block:PermalinkPage}
             {block:IfDarkTheme}theme-dark{/block:IfDarkTheme}
             ">

  <style>

  body {
      background-image: url('{image:Background}');
      font-family: {font:Font};
  }

  {CustomCSS}
  </style>

  {block:IfEnableFacebookButton}
  <div id="fb-root"></div>
  <script>(function(d, s, id) {
    var js, fjs = d.getElementsByTagName(s)[0];
    if (d.getElementById(id)) return;
    js = d.createElement(s); js.id = id;
    js.src = "//connect.facebook.net/ja_JP/all.js#xfbml=1";
    fjs.parentNode.insertBefore(js, fjs);
  }(document, 'script', 'facebook-jssdk'));</script>
  {/block:IfEnableFacebookButton}

  <div class="navbar">
    <div class="navbar-inner">
      <div class="container">
        <a class="brand" href="/">{Title}</a>
        <ul class="nav">
          {block:HasPages}
            {block:Pages}
            <li>
              <a href="{URL}">{Label}</a>
            </li>
            {/block:Pages}
          {/block:HasPages}
        </ul>
      </div>
    </div>
  </div>

  <div class="main container">
    <div class="wrapper section">

      {block:IndexPage}<!-- index -->
      <div class="header">
        <img class="header-image" src="{image:Main Image}" alt="{Title}">
      </div>

      <div class="navbar social-buttons">
        <div class="navbar-inner">
           <ul class="nav">
            {block:IfEnableFacebookButton}
            <li class="social-button">
              <div class="fb-like" data-send="false" data-layout="button_count" data-width="100" data-show-faces="false"></div>
            </li>
            {/block:IfEnableFacebookButton}
            {block:IfEnableTweetButton}
            <li class="social-button">
              <a href="https://twitter.com/share" class="twitter-share-button" data-lang="ja">ツイート</a>
              <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
            </li>
            {/block:IfEnableTweetButton}
            {block:IfEnableBookmarkButton}
            <li class="social-button">
              <a href="http://b.hatena.ne.jp/entry/" class="hatena-bookmark-button" data-hatena-bookmark-layout="standard-balloon" title="このエントリーをはてなブックマークに追加"><img src="http://b.st-hatena.com/images/entry-button/button-only.gif" alt="このエントリーをはてなブックマークに追加" width="20" height="20" style="border: none;" /></a><script type="text/javascript" src="http://b.st-hatena.com/js/bookmark_button.js" charset="utf-8" async="async"></script>
            </li>
            {/block:IfEnableBookmarkButton}
            {block:IfEnablePlus1Button}
            <li class="social-button">
              <div class="g-plusone" data-size="medium"></div>
              <script type="text/javascript">
                window.___gcfg = {lang: 'ja'};

                (function() {
                  var po = document.createElement('script'); po.type = 'text/javascript'; po.async = true;
                  po.src = 'https://apis.google.com/js/plusone.js';
                  var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(po, s);
                })();
              </script>
            </li>
            {/block:IfEnablePlus1Button}
            {block:IfStore01Name}
            <li>
              <a href="#buy" class="btn btn-primary"><i class="icon-shopping-cart"></i> 購入する</a>
            </li>
            {/block:IfStore01Name}
          </ul>
        </div>
      </div>

      <div class="content">
        <section class="section" id="spec">
          <div class="page-header">
            <h1>
              {Title}
            </h1>
          </div>
          {block:IfIntroduction}
          <h3>{text:Introduction Heading}</h3>
          <p class="introduction">
            {text:Introduction}
          </p>
          {/block:IfIntroduction}

          <div class="jacket-image">
            {block:IfJacketImage}
              <img src="{image:Jacket}" alt="{Title}">
            {/block:IfJacketImage}
            {block:IfNotJacketImage}
              <div class="jacket-noimage">
                NOW PRINTING
              </div>
            {/block:IfNotJacketImage}
          </div>
          <table class="table" id="buy">
            <tbody>
              <tr>
                <th>タイトル</th>
                <td>{Title}</td>
              </tr>
              <tr>
                <th>サークル</th>
                <td>{block:IfCircleURL}<a href="{text:Circle URL}" target="_blank">{/block:IfCircleURL}{text:Circle Name}{block:IfCircleURL}</a>{/block:IfCircleURL}</td>
              </tr>
              <tr>
                <th>仕様</th>
                <td>{text:Spec}</td>
              </tr>
              <tr>
                <th>頒布日</th>
                <td>{text:Release Date}</td>
              </tr>
              <tr>
                <th>頒布場所</th>
                <td>{text:Event Space Number}</td>
              </tr>
              <tr>
                <th>価格</th>
                <td>{text:Price}</td>
              </tr>
              {block:IfStore01Name}
              <tr>
                <th>購入</th>
                <td>
                  <ul>
                    <li>
                      <a href="{text:Store01 URL}" target="_blank">{text:Store01 Name}</a>
                    </li>
                    {block:IfStore02Name}
                    <li>
                      <a href="{text:Store02 URL}" target="_blank">{text:Store02 Name}</a>
                    </li>
                    {/block:IfStore02Name}
                    {block:IfStore03Name}
                    <li>
                      <a href="{text:Store03 URL}" target="_blank">{text:Store03 Name}</a>
                    </li>
                    {/block:IfStore03Name}
                    {block:IfStore04Name}
                    <li>
                      <a href="{text:Store04 URL}" target="_blank">{text:Store04 Name}</a>
                    </li>
                    {/block:IfStore04Name}
                  </ul>
                </td>
              {block:IfStore01Name}
              </tr>
              {/block:IfStore01Name}
            </tbody>
          </table>
        </section>
        {block:IfYoutubeEmbedCode}
        <section class="section" id="youtube">
          <h3>Youtube</h3>
          <div id="youtube-iframe">
            <iframe width="300" height="169" src="http://www.youtube.com/embed/{text:Youtube Embed Code}" frameborder="0" allowfullscreen></iframe>
          </div>
        </section>
        {/block:IfYoutubeEmbedCode}
        {block:IfNicovideoEmbedCode}
        <section class="section" id="nicovideo">
          <h3>NicoNico</h3>
          <script type="text/javascript" src="http://ext.nicovideo.jp/thumb_watch/{text:Nicovideo Embed Code}"></script>
        </section>
        {/block:IfNicovideoEmbedCode}
        {block:IfSoundcloudEmbedCode}
        <section class="section" id="demo">
          <h3>Soundcloud</h3>
          <iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=http%3A%2F%2Fapi.soundcloud.com%2Ftracks%2F{text:Soundcloud Embed Code}&amp;color=ff6600&amp;auto_play=false&amp;show_artwork=true"></iframe>
        </section>
        {/block:IfSoundcloudEmbedCode}
        <section class="section" id="tracklist">
          <div class="page-header">
            <h1>Tracklist</h1>
          </div>
          <table class="table">
            <tbody>
              {block:IfTrack01Title}
              <tr>
                <td class="track-number">01</td>
                <td>
                  <span class="track-title">{text:Track01 Title}</span>
                  <span class="track-meta">{text:Track01 Description}</span>
                </td>
              </tr>
              {/block:IfTrack01Title}
              {block:IfTrack02Title}
              <tr>
                <td class="track-number">02</td>
                <td>
                  <span class="track-title">{text:Track02 Title}</span>
                  <span class="track-meta">{text:Track02 Description}</span>
                </td>
              </tr>
              {/block:IfTrack02Title}
              {block:IfTrack03Title}
              <tr>
                <td class="track-number">03</td>
                <td>
                  <span class="track-title">{text:Track03 Title}</span>
                  <span class="track-meta">{text:Track03 Description}</span>
                </td>
              </tr>
              {/block:IfTrack03Title}
              {block:IfTrack04Title}
              <tr>
                <td class="track-number">04</td>
                <td>
                  <span class="track-title">{text:Track04 Title}</span>
                  <span class="track-meta">{text:Track04 Description}</span>
                </td>
              </tr>
              {/block:IfTrack04Title}
              {block:IfTrack05Title}
              <tr>
                <td class="track-number">05</td>
                <td>
                  <span class="track-title">{text:Track05 Title}</span>
                  <span class="track-meta">{text:Track05 Description}</span>
                </td>
              </tr>
              {/block:IfTrack05Title}
              {block:IfTrack06Title}
              <tr>
                <td class="track-number">06</td>
                <td>
                  <span class="track-title">{text:Track06 Title}</span>
                  <span class="track-meta">{text:Track06 Description}</span>
                </td>
              </tr>
              {/block:IfTrack06Title}
              {block:IfTrack07Title}
              <tr>
                <td class="track-number">07</td>
                <td>
                  <span class="track-title">{text:Track07 Title}</span>
                  <span class="track-meta">{text:Track07 Description}</span>
                </td>
              </tr>
              {/block:IfTrack07Title}
              {block:IfTrack08Title}
              <tr>
                <td class="track-number">08</td>
                <td>
                  <span class="track-title">{text:Track08 Title}</span>
                  <span class="track-meta">{text:Track08 Description}</span>
                </td>
              </tr>
              {/block:IfTrack08Title}
              {block:IfTrack09Title}
              <tr>
                <td class="track-number">09</td>
                <td>
                  <span class="track-title">{text:Track09 Title}</span>
                  <span class="track-meta">{text:Track09 Description}</span>
                </td>
              </tr>
              {/block:IfTrack09Title}
              {block:IfTrack10Title}
              <tr>
                <td class="track-number">10</td>
                <td>
                  <span class="track-title">{text:Track10 Title}</span>
                  <span class="track-meta">{text:Track10 Description}</span>
                </td>
              </tr>
              {/block:IfTrack10Title}
            </tbody>
          </table>
        </section>
        <section class="section" id="staff">
          <div class="page-header">
            <h1>Staff</h1>
          </div>
          <ul class="thumbnails">
            {block:IfStaff01Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff01 Role}</dt>
                <dd>{text:Staff01 Name}
                  {block:IfStaff01URL}
                  <a class="website" href="{text:Staff01 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff01URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff01Name}
            {block:IfStaff02Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff02 Role}</dt>
                <dd>{text:Staff02 Name}
                  {block:IfStaff02URL}
                  <a class="website" href="{text:Staff02 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff02URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff02Name}
            {block:IfStaff03Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff03 Role}</dt>
                <dd>{text:Staff03 Name}
                  {block:IfStaff03URL}
                  <a class="website" href="{text:Staff03 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff03URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff03Name}
            {block:IfStaff04Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff04 Role}</dt>
                <dd>{text:Staff04 Name}
                  {block:IfStaff04URL}
                  <a class="website" href="{text:Staff04 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff04URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff04Name}
            {block:IfStaff05Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff05 Role}</dt>
                <dd>{text:Staff05 Name}
                  {block:IfStaff05URL}
                  <a class="website" href="{text:Staff05 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff05URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff05Name}
            {block:IfStaff06Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff06 Role}</dt>
                <dd>{text:Staff06 Name}
                  {block:IfStaff06URL}
                  <a class="website" href="{text:Staff06 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff06URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff06Name}
            {block:IfStaff07Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff07 Role}</dt>
                <dd>{text:Staff07 Name}
                  {block:IfStaff07URL}
                  <a class="website" href="{text:Staff07 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff07URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff07Name}
            {block:IfStaff08Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff08 Role}</dt>
                <dd>{text:Staff08 Name}
                  {block:IfStaff08URL}
                  <a class="website" href="{text:Staff08 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff08URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff08Name}
            {block:IfStaff09Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff09 Role}</dt>
                <dd>{text:Staff09 Name}
                  {block:IfStaff09URL}
                  <a class="website" href="{text:Staff09 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff09URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff09Name}
            {block:IfStaff10Name}
            <li class="span3">
              <dl>
                <dt>{text:Staff10 Role}</dt>
                <dd>{text:Staff10 Name}
                  {block:IfStaff10URL}
                  <a class="website" href="{text:Staff10 URL}" target="_blank">
                    Website
                  </a>
                  {/block:IfStaff10URL}
                </dd>
              </dl>
            </li>
            {/block:IfStaff10Name}
          </ul>
        </section>
        {block:IfBanner1Image}
        <section id="banner">
          <div class="page-header">
            <h1>Banner</h1>
          </div>
          <span class="banner-box">
            <img src="{image:Banner1}" alt="{Title}">
          </span>
          {/block:IfBanner1Image}
          {block:IfBanner2Image}
          <span class="banner-box">
            <img src="{image:Banner2}" alt="{Title}">
          </span>
          {/block:IfBanner2Image}
        {block:IfBanner1Image}
        </section>
        {/block:IfBanner1Image}
      </div><!-- /content -->
      {/block:IndexPage}<!-- END Index -->

      {block:PermalinkPage}<!-- Permalink -->
        {block:Posts}
        <div class="content">
          {block:Text}<!-- 固定ページ -->
            {block:Title}
              <div class="page-header">
                <h1><a href="{Permalink}" class="permalink">{Title}</a></h1>
              </div>
            {/block:Title}
            <div class="entry-content">
              {Body}
            </div>
          {/block:Text}
        </div>
        {/block:Posts}

      {/block:PermalinkPage}<!-- END Permalink -->

    </div><!-- /wrapper -->
  </div><!-- /main container -->

  <footer id="footer">
    <div class="container">
      <small>
        <p>
          ©{CopyrightYears} {Title}<br/>
          {text:Footer Text}
        </p>
        <p>
          <a href="http://sanographix.github.com/tumblr/tokusetsu/" target="_blank">Tokusetsu</a> theme designed by <a href="http://www.sanographix.net/" target="_blank">SANOGRAPHIX.NET</a>
        </p>
      </small>
    </div>
  </footer>

  <script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
  <script src="//cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.3/jquery.easing.min.js"></script>
  <script src="//cdnjs.cloudflare.com/ajax/libs/retina.js/1.0.1/retina.js"></script>
  <script src="//cdnjs.cloudflare.com/ajax/libs/fitvids/1.0.1/jquery.fitvids.min.js"></script>
  <script src="http://sanographix.github.com/public/tumblr/tokusetsu/js/jquery.options.js"></script>

</body>
</html>
