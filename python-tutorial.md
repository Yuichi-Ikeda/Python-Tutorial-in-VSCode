





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-dxFVfmRlzgntw9xnKsYVxQUyV8JZifjI76hlssNAlbCn/gOmgfo4skfRATXTzQ8qG+NNgIh6fvkeQttpFQRpQQ==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-7711557e6465ce09edc3dc672ac615c5.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-n8ma4pfv4AZutC1jZMb9DCqVgJq/T7LyrcIrc1QTof+1rn00RPeT5iGHD5KY0zUaxYhKFMXvv+DX7pSNkCIblg==" rel="stylesheet" href="https://github.githubassets.com/assets/github-9fc99ae297efe0066eb42d6364c6fd0c.css" />
    
    
    
    


  <meta name="viewport" content="width=device-width">
  
  <title>vscode-docs/python-tutorial.md at master · Yuichi-Ikeda/vscode-docs</title>
    <meta name="description" content="Public documentation for Visual Studio Code. Contribute to Yuichi-Ikeda/vscode-docs development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars2.githubusercontent.com/u/15528536?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="Yuichi-Ikeda/vscode-docs" /><meta name="twitter:description" content="Public documentation for Visual Studio Code. Contribute to Yuichi-Ikeda/vscode-docs development by creating an account on GitHub." />
    <meta property="og:image" content="https://avatars2.githubusercontent.com/u/15528536?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="Yuichi-Ikeda/vscode-docs" /><meta property="og:url" content="https://github.com/Yuichi-Ikeda/vscode-docs" /><meta property="og:description" content="Public documentation for Visual Studio Code. Contribute to Yuichi-Ikeda/vscode-docs development by creating an account on GitHub." />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NDg4MTc5MDk1OjIyNGJmZmJlODNhYzZkY2JmMDY5ZTkwNmVkNzEyZmZjMGI2OWE1YjVjMmNmYjIwOGUxNjAwMzA0ZTY5YmVjMDQ=--7a87b02c6099d181209b9ff70252e53e5fad4e72">
  <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="request-id" content="4752:2D4F:1C9720:2884DA:5E290C29" data-pjax-transient>



  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

    <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="4752:2D4F:1C9720:2884DA:5E290C29" /><meta name="octolytics-dimension-region_edge" content="ap-southeast-1" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="6692786412960603886" /><meta name="octolytics-actor-id" content="15528536" /><meta name="octolytics-actor-login" content="Yuichi-Ikeda" /><meta name="octolytics-actor-hash" content="28a10b7ef3a471861bf5458c5514af6b8e2ed16c768311f5530ea82185b3df8a" />

<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="5271ad1cb88f62640a0e11b9f22c3d85">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="Yuichi-Ikeda">

      <meta name="expected-hostname" content="github.com">

      <meta name="js-proxy-site-detection-payload" content="Zjk4ZmQwYmY5MTc4YWU3Mzk5NjI0MjI3MTZhMjczZDVhYjVjNjFjYjE4ODE4MGMzNzU2ZTY5ODA1NWE3ZjNlY3x7InJlbW90ZV9hZGRyZXNzIjoiMTY3LjIyMC4yMzIuMjAwIiwicmVxdWVzdF9pZCI6IjQ3NTI6MkQ0RjoxQzk3MjA6Mjg4NERBOjVFMjkwQzI5IiwidGltZXN0YW1wIjoxNTc5NzQ4NDE0LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS,NOTIFY_ON_BLOCK,RELATED_ISSUES,GHE_CLOUD_TRIAL">

    <meta name="html-safe-nonce" content="a225cddab3955e43f87dc35c6059a8fc19669576">

  <meta http-equiv="x-pjax-version" content="5ef375297f22f852aab67c68a1cb036d">
  

      <link href="https://github.com/Yuichi-Ikeda/vscode-docs/commits/master.atom" rel="alternate" title="Recent Commits to vscode-docs:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/Yuichi-Ikeda/vscode-docs git https://github.com/Yuichi-Ikeda/vscode-docs.git">

  <meta name="octolytics-dimension-user_id" content="15528536" /><meta name="octolytics-dimension-user_login" content="Yuichi-Ikeda" /><meta name="octolytics-dimension-repository_id" content="235710207" /><meta name="octolytics-dimension-repository_nwo" content="Yuichi-Ikeda/vscode-docs" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="true" /><meta name="octolytics-dimension-repository_parent_id" content="41443539" /><meta name="octolytics-dimension-repository_parent_nwo" content="microsoft/vscode-docs" /><meta name="octolytics-dimension-repository_network_root_id" content="41443539" /><meta name="octolytics-dimension-repository_network_root_nwo" content="microsoft/vscode-docs" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <span class="Progress progress-pjax-loader position-fixed width-full js-pjax-loader-bar">
      <span class="progress-pjax-loader-bar top-0 left-0" style="width: 0%;"></span>
    </span>

    
    
    


          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
        <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="235710207" data-scoped-search-url="/Yuichi-Ikeda/vscode-docs/search" data-unscoped-search-url="/search" action="/Yuichi-Ikeda/vscode-docs/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=Xn179iRJAmMTQ4a4xKEtGN/5uvCo5jpCMwo5OLRXDeJl40AxKt0FV2p//sh7e4nt17yM0ZDhcX5ZJiMTVRf9+w=="
          spellcheck="false"
          autocomplete="off"
          >
            <input class="js-data-jump-to-suggestions-path-csrf" type="hidden" value="van+QKegkDfJVmAWJ3GvXt/qHawcvKkQ8uasm6yymMGGN8WHqTSXA7BqGGaYqwur168rjSS74iyYyrawTfJo2A==">
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


      <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>
    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
        Marketplace
</a>      

    </div>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>


    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" href="https://github.com/Yuichi-Ikeda">
      <img class="avatar" height="20" width="20" alt="@Yuichi-Ikeda" src="https://avatars2.githubusercontent.com/u/15528536?s=60&amp;v=4" />
      Yuichi-Ikeda
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="wmZLwbOlUsErX4WTMJAs6/MFYPqkVX36Y+M+DfZ1f9JHaFCvA7H2gbW2jUl73VlfQhH7QfpxwcP7dqXbxHXKig==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"/></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
    <a class="Header-link" href="/Yuichi-Ikeda">Yuichi-Ikeda</a>
    /
    <a class="Header-link" href="/Yuichi-Ikeda/vscode-docs">vscode-docs</a>

</div>
    </div>


    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      

    <a aria-label="You have no unread notifications" class="Header-link notification-indicator position-relative tooltipped tooltipped-sw js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:15528536" href="/notifications">
        <span class="js-indicator-modifier mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <a role="menuitem" class="dropdown-item" href="/new/project" data-ga-click="Header, create new project">
    New project
  </a>

  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
  <details class="details-overlay details-reset js-feature-preview-indicator-container" data-feature-preview-indicator-src="/users/Yuichi-Ikeda/feature_preview/indicator_check.json">

  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img alt="@Yuichi-Ikeda" class="avatar" src="https://avatars1.githubusercontent.com/u/15528536?s=40&amp;v=4" height="20" width="20">
      <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/Yuichi-Ikeda" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">Yuichi-Ikeda</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container
    user-status-compact rounded-1 px-2 py-1 mt-2
    border
  " data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit "
      role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:15528536,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:15528536,&quot;client_id&quot;:&quot;1558285768.1578360558&quot;,&quot;originating_request_id&quot;:&quot;4752:2D4F:1C9720:2884DA:5E290C29&quot;,&quot;originating_url&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md&quot;,&quot;referrer&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/tree/master/docs/python&quot;}}" data-hydro-click-hmac="37e4ae02f3722b595476f230f56d6b1d7297a69358a8af21cd957859efd09a80">
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header
          d-inline-block v-align-middle
            user-status-emoji-only-header circle
            pr-2
"
            style="max-width: 29px"
          >
          <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
            <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
          </div>
        </div>
        <div class="
          d-inline-block v-align-middle
          
          
           css-truncate css-truncate-target 
           user-status-message-wrapper f6"
           style="line-height: 20px;" >
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
              <span class="text-gray ml-2">Set status</span>
          </div>
        </div>
      </div>
    </summary>
    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="csrX34AS8BQ8ucbAuSSAqJuOOKgaG4it/jXR2q8ytXR6enG8BOHM7WVwMxD146hmlPqHmapAX0gwcPKdc5TjWA==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
                  </span>
                </button>
              </span>
              <text-expander keys=": @" data-mention-url="/autocomplete/user-suggestions" data-emoji-url="/autocomplete/emoji">
                <input
                  type="text"
                  autocomplete="off"
                  data-no-org-url="/autocomplete/user-suggestions"
                  data-org-url="/suggestions?mention_suggester=1"
                  data-maxlength="80"
                  class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field"
                  placeholder="What's happening?"
                  name="message"
                  value=""
                  aria-label="What is your current status?">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true-compact-true" id="limited-availability-truncate-true-compact-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
            

<div class="d-inline-block f5 mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2020-01-23T12:30:14+09:00">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2020-01-23T13:00:14+09:00">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2020-01-23T16:00:14+09:00">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2020-01-23T23:59:59+09:00">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2020-01-26T23:59:59+09:00">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit" disabled class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button" disabled class="width-full js-clear-user-status-button btn ml-2 ">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>


    <a role="menuitem" class="dropdown-item" href="/Yuichi-Ikeda" data-ga-click="Header, go to profile, text:your profile">Your profile</a>

    <a role="menuitem" class="dropdown-item" href="/Yuichi-Ikeda?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/Yuichi-Ikeda?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/Yuichi-Ikeda?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>





    <div role="none" class="dropdown-divider"></div>
      
<div id="feature-enrollment-toggle" class="hide-sm hide-md feature-preview-details position-relative">
  <button
    type="button"
    class="dropdown-item btn-link"
    role="menuitem"
    data-feature-preview-trigger-url="/users/Yuichi-Ikeda/feature_previews"
    data-feature-preview-close-details="{&quot;event_type&quot;:&quot;feature_preview.clicks.close_modal&quot;,&quot;payload&quot;:{&quot;client_id&quot;:&quot;1558285768.1578360558&quot;,&quot;originating_request_id&quot;:&quot;4752:2D4F:1C9720:2884DA:5E290C29&quot;,&quot;originating_url&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md&quot;,&quot;referrer&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/tree/master/docs/python&quot;,&quot;user_id&quot;:15528536}}"
    data-feature-preview-close-hmac="8f47c68384038743f541d15f72d9a8964f4b7ba474e89447ec1e55996f652065"
    data-hydro-click="{&quot;event_type&quot;:&quot;feature_preview.clicks.open_modal&quot;,&quot;payload&quot;:{&quot;link_location&quot;:&quot;user_dropdown&quot;,&quot;client_id&quot;:&quot;1558285768.1578360558&quot;,&quot;originating_request_id&quot;:&quot;4752:2D4F:1C9720:2884DA:5E290C29&quot;,&quot;originating_url&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md&quot;,&quot;referrer&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/tree/master/docs/python&quot;,&quot;user_id&quot;:15528536}}"
    data-hydro-click-hmac="c7626f9e7cdab94aec7470e0480fb9c35f4b74b63fb4b8b1714ee1c8279fa086"
  >
    Feature preview
  </button>
    <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
</div>

    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="i7VrsqEZRtoh5oJsxwpL2zl6Efy1utOg49P/WPFWMk8Ou3DcEQ3imr8PiraMRz5viG6KR+ueb5l7RmSOw1aHFw==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
      <input type="text" name="required_field_2f53" hidden="hidden" class="form-control" />
<input type="hidden" name="timestamp" value="1579748414303" class="form-control" />
<input type="hidden" name="timestamp_secret" value="cf1a6835d1085b53c15cbf536ed6eadb633a0d060f154e3c39005d239f01bfcd" class="form-control" />

</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      

  

      <div class="border-bottom shelf intro-shelf js-notice mb-0 pb-4">
  <div class="width-full container">
    <div class="width-full mx-auto shelf-content">
      <h2 class="shelf-title">Learn Git and GitHub without any code!</h2>
      <p class="shelf-lead">
          Using the Hello World guide, you’ll start a branch, write comments, and open a pull request.
      </p>
      <a class="btn btn-primary shelf-cta" target="_blank" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;READ_GUIDE&quot;,&quot;repository_id&quot;:235710207,&quot;client_id&quot;:&quot;1558285768.1578360558&quot;,&quot;originating_request_id&quot;:&quot;4752:2D4F:1C9720:2884DA:5E290C29&quot;,&quot;originating_url&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md&quot;,&quot;referrer&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/tree/master/docs/python&quot;,&quot;user_id&quot;:15528536}}" data-hydro-click-hmac="fcffd4e5c16f26703014a06196dd4f251bf9148da6c8f4fd03d72d932a74fc25" href="https://guides.github.com/activities/hello-world/">Read the guide</a>
    </div>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="shelf-dismiss js-notice-dismiss" action="/dashboard/dismiss_bootcamp" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="delete" /><input type="hidden" name="authenticity_token" value="waqhMkF5hgJ1a0iT8hKW4ucFQGhZwM1KRowomu0/9sWqZRMGTPCDbf4lqgufOXUmqWVgfaHQW3YhyV2BOXV3fQ==" />
      <button name="button" type="submit" class="mr-1 close-button tooltipped tooltipped-w" aria-label="Hide this notice forever" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;DISMISS_BANNER&quot;,&quot;repository_id&quot;:235710207,&quot;client_id&quot;:&quot;1558285768.1578360558&quot;,&quot;originating_request_id&quot;:&quot;4752:2D4F:1C9720:2884DA:5E290C29&quot;,&quot;originating_url&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md&quot;,&quot;referrer&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/tree/master/docs/python&quot;,&quot;user_id&quot;:15528536}}" data-hydro-click-hmac="ac4fee25bea51264c6230cf16fd03c45ebc99e24f54c5165e1a6fb80d19d93de">
        <svg aria-label="Hide this notice forever" class="octicon octicon-x v-align-text-top" viewBox="0 0 12 16" version="1.1" width="12" height="16" role="img"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
</button></form>  </div>
</div>










  <div class=" pagehead repohead readability-menu experiment-repo-nav pt-0 pt-lg-4 ">

    <div class="container-lg mb-4 p-responsive d-none d-lg-flex">

      <div class="flex-auto min-width-0 width-fit mr-3">
        <h1 class="public  d-flex flex-wrap flex-items-center break-word float-none">
    <svg class="octicon octicon-repo-forked mr-1" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
  <span class="author" itemprop="author">
    <a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/users/Yuichi-Ikeda/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/Yuichi-Ikeda">Yuichi-Ikeda</a>
  </span>
  <span class="path-divider">/</span>
  <strong itemprop="name" class="mr-2">
    <a data-pjax="#js-repo-pjax-container" href="/Yuichi-Ikeda/vscode-docs">vscode-docs</a>
  </strong>
  
</h1>

  <span class="fork-flag mt-1" data-repository-hovercards-enabled>
    <span class="text">forked from <a data-hovercard-type="repository" data-hovercard-url="/microsoft/vscode-docs/hovercard" href="/microsoft/vscode-docs">microsoft/vscode-docs</a></span>
  </span>

      </div>

      <ul class="pagehead-actions flex-shrink-0">




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="wZzG294N9+XiyQtBpdb9R1ougQl9qCex53EUdt0uRIQYHtbo2jxnzTaHq8y3X6L4UQjFkhFecMJZikLEWSCbvQ==" />      <input type="hidden" name="repository_id" value="235710207">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:235710207,&quot;client_id&quot;:&quot;1558285768.1578360558&quot;,&quot;originating_request_id&quot;:&quot;4752:2D4F:1C9720:2884DA:5E290C29&quot;,&quot;originating_url&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md&quot;,&quot;referrer&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/tree/master/docs/python&quot;,&quot;user_id&quot;:15528536}}" data-hydro-click-hmac="ed7290469db3e392b2db5b54f3bdaf52a0d6002085c287db9fcc70aaeb01a2e2" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/Yuichi-Ikeda/vscode-docs/watchers"
          aria-label="0 users are watching this repository">
          0
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <form class="starred js-social-form" action="/Yuichi-Ikeda/vscode-docs/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="J6G9I2vgGEeeeN21j9xOkHhYmMA5foAfV6UFepNi5dtyA9Qm6rWRkeabFlAgfCsBOkeBiULJ0dAwHKITOEBQ8A==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar Yuichi-Ikeda/vscode-docs" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:235710207,&quot;client_id&quot;:&quot;1558285768.1578360558&quot;,&quot;originating_request_id&quot;:&quot;4752:2D4F:1C9720:2884DA:5E290C29&quot;,&quot;originating_url&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md&quot;,&quot;referrer&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/tree/master/docs/python&quot;,&quot;user_id&quot;:15528536}}" data-hydro-click-hmac="4bec2026924b87050c22496c82610fa7887bada954bb0a0276a696d72d15ee16" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg aria-label="star" height="16" class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" role="img"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>

        Unstar
</button>        <a class="social-count js-social-count" href="/Yuichi-Ikeda/vscode-docs/stargazers"
           aria-label="0 users starred this repository">
           0
        </a>
</form>
    <form class="unstarred js-social-form" action="/Yuichi-Ikeda/vscode-docs/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="OJq27LEkekz/6cwLRxuS8Rkzhcsf86qQjrUEhemnZUF40nMnjO4EQS9N4p1k2nJFQecnXb1JWxbUvbf3iLqL2w==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star Yuichi-Ikeda/vscode-docs" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:235710207,&quot;client_id&quot;:&quot;1558285768.1578360558&quot;,&quot;originating_request_id&quot;:&quot;4752:2D4F:1C9720:2884DA:5E290C29&quot;,&quot;originating_url&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/python-tutorial.md&quot;,&quot;referrer&quot;:&quot;https://github.com/Yuichi-Ikeda/vscode-docs/tree/master/docs/python&quot;,&quot;user_id&quot;:15528536}}" data-hydro-click-hmac="51868784ce6c6ebe7ba8d4aebe27ffc76f5a38e43cb45c42eed45fdafa6bdc2a" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg aria-label="star" height="16" class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" role="img"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>

        Star
</button>        <a class="social-count js-social-count" href="/Yuichi-Ikeda/vscode-docs/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
        <span class="btn btn-sm btn-with-count disabled tooltipped tooltipped-sw" aria-label="Cannot fork because you own this repository and are not a member of any organizations.">
          <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
          Fork
</span>
    <a href="/Yuichi-Ikeda/vscode-docs/network/members" class="social-count"
       aria-label="2206 users forked this repository">
      2.2k
    </a>
  </li>
</ul>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax clearfix container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /Yuichi-Ikeda/vscode-docs" href="/Yuichi-Ikeda/vscode-docs">
      <div class="d-inline"><svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg></div>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>



  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" data-skip-pjax="true" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /Yuichi-Ikeda/vscode-docs/pulls" href="/Yuichi-Ikeda/vscode-docs/pulls">
      <div class="d-inline"><svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0010 15a1.993 1.993 0 001-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 00-1 3.72v6.56A1.993 1.993 0 002 15a1.993 1.993 0 001-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg></div>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="4">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement" class="position-relative float-left">
      <a data-hotkey="g w" data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="repo_actions /Yuichi-Ikeda/vscode-docs/actions" href="/Yuichi-Ikeda/vscode-docs/actions">
        <div class="d-inline"><svg class="octicon octicon-play" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 8A7 7 0 110 8a7 7 0 0114 0zm-8.223 3.482l4.599-3.066a.5.5 0 000-.832L5.777 4.518A.5.5 0 005 4.934v6.132a.5.5 0 00.777.416z"/></svg></div>
        Actions
</a>
    </span>

    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /Yuichi-Ikeda/vscode-docs/projects" href="/Yuichi-Ikeda/vscode-docs/projects">
      <div class="d-inline"><svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"/></svg></div>
      Projects
      <span class="Counter" >0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /Yuichi-Ikeda/vscode-docs/wiki" href="/Yuichi-Ikeda/vscode-docs/wiki">
      <div class="d-inline"><svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg></div>
      Wiki
</a>
    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy token_scanning code_scanning /Yuichi-Ikeda/vscode-docs/network/alerts" href="/Yuichi-Ikeda/vscode-docs/network/alerts">
      <div class="d-inline"><svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"/></svg></div>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /Yuichi-Ikeda/vscode-docs/pulse" href="/Yuichi-Ikeda/vscode-docs/pulse">
      <div class="d-inline"><svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg></div>
      Insights
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_settings repo_branch_settings hooks integration_installations repo_keys_settings issue_template_editor secrets_settings key_links_settings /Yuichi-Ikeda/vscode-docs/settings" href="/Yuichi-Ikeda/vscode-docs/settings">
      <div class="d-inline"><svg class="octicon octicon-gear" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 8.77v-1.6l-1.94-.64-.45-1.09.88-1.84-1.13-1.13-1.81.91-1.09-.45-.69-1.92h-1.6l-.63 1.94-1.11.45-1.84-.88-1.13 1.13.91 1.81-.45 1.09L0 7.23v1.59l1.94.64.45 1.09-.88 1.84 1.13 1.13 1.81-.91 1.09.45.69 1.92h1.59l.63-1.94 1.11-.45 1.84.88 1.13-1.13-.92-1.81.47-1.09L14 8.75v.02zM7 11c-1.66 0-3-1.34-3-3s1.34-3 3-3 3 1.34 3 3-1.34 3-3 3z"/></svg></div>
      Settings
</a>
</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /Yuichi-Ikeda/vscode-docs" href="/Yuichi-Ikeda/vscode-docs">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>



    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /Yuichi-Ikeda/vscode-docs/pulls" href="/Yuichi-Ikeda/vscode-docs/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="4">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /Yuichi-Ikeda/vscode-docs/projects" href="/Yuichi-Ikeda/vscode-docs/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="5">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /Yuichi-Ikeda/vscode-docs/wiki" href="/Yuichi-Ikeda/vscode-docs/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="6">
</a>      </span>

      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy token_scanning code_scanning /Yuichi-Ikeda/vscode-docs/network/alerts" href="/Yuichi-Ikeda/vscode-docs/network/alerts">
        <span itemprop="name">Security</span>
        <meta itemprop="position" content="7">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /Yuichi-Ikeda/vscode-docs/pulse" href="/Yuichi-Ikeda/vscode-docs/pulse">
        Pulse
</a>

  </nav>
</div>


  </div>
<div class="container-lg clearfix new-discussion-timeline experiment-repo-nav  p-responsive">
  <div class="repository-content ">

    
    


  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/Yuichi-Ikeda/vscode-docs/blob/ff847d93f82532b587ceac71780a12cfc71c80c2/docs/python/python-tutorial.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:4ac430ab08d5a420c94af02763f3b626 -->
      

    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay branch-select-menu " id="branch-select-menu">
  <summary class="btn btn-sm css-truncate"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
    <span class="dropdown-caret"></span>
  </summary>

  <details-menu class="SelectMenu SelectMenu--hasFilter" src="/Yuichi-Ikeda/vscode-docs/refs/master/docs/python/python-tutorial.md?source_action=show&amp;source_controller=blob" preload>
    <div class="SelectMenu-modal">
      <include-fragment class="SelectMenu-loading" aria-label="Menu is loading">
        <svg class="octicon octicon-octoface anim-pulse" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
      </include-fragment>
    </div>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/Yuichi-Ikeda/vscode-docs/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="docs/python/python-tutorial.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/Yuichi-Ikeda/vscode-docs"><span>vscode-docs</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/Yuichi-Ikeda/vscode-docs/tree/master/docs"><span>docs</span></a></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/Yuichi-Ikeda/vscode-docs/tree/master/docs/python"><span>python</span></a></span><span class="separator">/</span><strong class="final-path">python-tutorial.md</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/Yuichi-Ikeda/vscode-docs/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="docs/python/python-tutorial.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>

    



    <include-fragment src="/Yuichi-Ikeda/vscode-docs/contributors/master/docs/python/python-tutorial.md" class="Box Box--condensed commit-loader">
      <div class="Box-body bg-blue-light f6">
        Fetching contributors&hellip;
      </div>

      <div class="Box-body d-flex flex-items-center" >
          <img alt="" class="loader-loading mr-2" src="https://github.githubassets.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" height="16" />
        <span class="text-red h6 loader-error">Cannot retrieve contributors at this time</span>
      </div>
</include-fragment>




    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">
  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">

      323 lines (192 sloc)
      <span class="file-info-divider"></span>
    21.1 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/python-tutorial.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/Yuichi-Ikeda/vscode-docs/blame/master/docs/python/python-tutorial.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/Yuichi-Ikeda/vscode-docs/commits/master/docs/python/python-tutorial.md">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw hide-sm"
               href="x-github-client://openRepo/https://github.com/Yuichi-Ikeda/vscode-docs?branch=master&amp;filepath=docs%2Fpython%2Fpython-tutorial.md"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:windows">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/Yuichi-Ikeda/vscode-docs/edit/master/docs/python/python-tutorial.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="GZhnWBjU3zyNILAf777bC8deJm6T8bUGtKdd6KZ+M5/7W5NxLpRlvfX7nMJsCmLt3EONWoqHExf96pQWhM+Qqw==" />
              <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
                aria-label="Edit this file" data-hotkey="e" data-disable-with>
                <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 011.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
              </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/Yuichi-Ikeda/vscode-docs/delete/master/docs/python/python-tutorial.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="bvMF0CijPq3vffwD/fqQi1lKCZLUOMfN4scN/5v9k18zSbBHTfjxIYWk7ZJsf4ZsPepy6tA/YFbQ6XuK3EAcpQ==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Delete this file" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><table data-table-type="yaml-metadata">
  <thead>
  <tr>
  <th>Order</th>
  <th>Area</th>
  <th>TOCTitle</th>
  <th>ContentId</th>
  <th>PageTitle</th>
  <th>DateApproved</th>
  <th>MetaDescription</th>
  <th>MetaSocialImage</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>1</div></td>
  <td><div>python</div></td>
  <td><div>Tutorial</div></td>
  <td><div>77828f36-ae45-4887-b25c-34545edd52d3</div></td>
  <td><div>Get Started Tutorial for Python in Visual Studio Code</div></td>
  <td><div>07/18/2019</div></td>
  <td><div>A Python hello world tutorial using the Python extension in Visual Studio Code (a great Python IDE like PyCharm, if not the best Python IDE)</div></td>
  <td><div>images/tutorial/social.png</div></td>
  </tr>
  </tbody>
</table>

<h1><a id="user-content-getting-started-with-python-in-vs-code" class="anchor" aria-hidden="true" href="#getting-started-with-python-in-vs-code"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Getting Started with Python in VS Code</h1>
<p>In this tutorial, you use Python 3 to create the simplest Python "Hello World" application in Visual Studio Code. By using the Python extension, you make VS Code into a great lightweight Python IDE (which you may find a productive alternative to PyCharm).</p>
<p>This tutorial introduces you to VS Code as a Python environment, primarily how to edit, run, and debug code through the following tasks:</p>
<ul>
<li>Write, run, and debug a Python "Hello World" Application</li>
<li>Learn how to install packages by creating Python virtual environments</li>
<li>Write a simple Python script to plot figures within VS Code</li>
</ul>
<p>This tutorial is not intended to teach you Python itself. Once you are familiar with the basics of VS Code, you can then follow any of the <a href="https://wiki.python.org/moin/BeginnersGuide/Programmers" rel="nofollow">programming tutorials on python.org</a> within the context of VS Code for an introduction to the language.</p>
<p>If you have any problems, feel free to file an issue for this tutorial in the <a href="https://github.com/Microsoft/vscode-docs/issues">VS Code documentation repository</a>.</p>
<blockquote>
<p><strong>Note</strong>: You can use VS Code with Python 2 with this tutorial, but you need to make appropriate changes to the code, which are not covered here.</p>
</blockquote>
<h2><a id="user-content-prerequisites" class="anchor" aria-hidden="true" href="#prerequisites"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Prerequisites</h2>
<p>To successfully complete this tutorial, you need to first setup your Python  development environment. Specifically, this tutorial requires:</p>
<ul>
<li>VS Code</li>
<li>VS Code Python extension</li>
<li>Python 3</li>
</ul>
<h2><a id="user-content-install-visual-studio-code-and-the-python-extension" class="anchor" aria-hidden="true" href="#install-visual-studio-code-and-the-python-extension"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Install Visual Studio Code and the Python Extension</h2>
<ol>
<li>
<p>If you have not already done so, install <a href="https://code.visualstudio.com/" rel="nofollow">VS Code</a></p>
</li>
<li>
<p>Next, install the <a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python" rel="nofollow">Python extension for VS Code</a> from the Visual Studio Marketplace. For additional details on installing extensions, see <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/editor/extension-gallery.md">Extension Marketplace</a>. The Python extension is named <strong>Python</strong> and published by Microsoft.</p>
<p><a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python" rel="nofollow"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/python-extension-marketplace.png" alt="Python extension on Marketplace" style="max-width:100%;"></a></p>
</li>
</ol>
<h2><a id="user-content-install-a-python-interpreter" class="anchor" aria-hidden="true" href="#install-a-python-interpreter"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Install a Python interpreter</h2>
<p>Along with the Python extension, you need to install a Python interpreter. Which interpreter you use is dependent on your specific needs, but some guidance is provided below.</p>
<h3><a id="user-content-windows" class="anchor" aria-hidden="true" href="#windows"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows</h3>
<p>Install <a href="https://www.python.org/downloads/" rel="nofollow">Python from python.org</a>. You can typically use the <strong>Download Python</strong> button that appears first on the page to download the latest version.</p>
<blockquote>
<p><strong>Note</strong>: If you don't have admin access, an additional option for installing Python on Windows is to use the Microsoft Store. The Microsoft Store provides installs of <a href="https://www.microsoft.com/en-us/p/python-37/9nj46sx7x90p" rel="nofollow">Python 3.7</a> and <a href="https://www.microsoft.com/en-us/p/python-38/9mssztt1n39l" rel="nofollow">Python 3.8</a>. Be aware that you might have compatibility issues with some packages using this method.</p>
</blockquote>
<p>For additional information about Python on Windows, see <a href="https://docs.python.org/3.7/using/windows.html" rel="nofollow">Using Python on Windows at Python.org</a></p>
<h3><a id="user-content-macos" class="anchor" aria-hidden="true" href="#macos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>macOS</h3>
<p>The system install of Python on macOS is not supported. Instead, an installation through <a href="https://brew.sh/" rel="nofollow">Homebrew</a> is recommended. To install Python using Homebrew on macOS use <code>brew install python3</code> at the Terminal prompt.</p>
<blockquote>
<p><strong>Note</strong> On macOS, make sure the location of your VS Code installation is included in your PATH environment variable.  See <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/setup/mac.md#launching-from-the-command-line">these setup instructions</a> for more information.</p>
</blockquote>
<h3><a id="user-content-linux" class="anchor" aria-hidden="true" href="#linux"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Linux</h3>
<p>The built-in Python 3 installation on Linux works well, but to install other Python packages you must install <code>pip</code> with <a href="https://pip.pypa.io/en/stable/installing/#installing-with-get-pip-py" rel="nofollow"><code>get-pip.py</code></a>.</p>
<h3><a id="user-content-other-options" class="anchor" aria-hidden="true" href="#other-options"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Other options</h3>
<ul>
<li>
<p><strong>Data Science</strong>: If your primary purpose for using Python is Data Science, then you might consider a download from <a href="https://www.anaconda.com/download/" rel="nofollow">Anaconda</a>. Anaconda provides not just a Python interpreter, but many useful libraries and tools for data science.</p>
</li>
<li>
<p><strong>Windows Subsystem for Linux</strong>: If you are working on Windows and want a Linux environment for working with Python, the <a href="https://docs.microsoft.com/windows/wsl/about" rel="nofollow">Windows Subsystem for Linux</a> (WSL) is an option for you. If you choose this option, you'll also want to install the <a href="https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl" rel="nofollow">Remote - WSL extension</a>. For more information about using WSL with VS Code, see <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/remote/remote-overview.md">VS Code Remote Development</a> or try the <a href="/Yuichi-Ikeda/vscode-docs/blob/master/remote-tutorials/wsl/getting-started.md">Working in WSL tutorial</a>, which will walk you through setting up WSL, installing Python, and creating a Hello World application running in WSL.</p>
</li>
</ul>
<h2><a id="user-content-verify-the-python-installation" class="anchor" aria-hidden="true" href="#verify-the-python-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Verify the Python installation</h2>
<p>To verify that you've installed Python successfully on your machine, run one of the following commands (depending on your operating system):</p>
<ul>
<li>
<p>Linux/macOS: open a Terminal Window and type the following command:</p>
<div class="highlight highlight-source-shell"><pre>python3 --version</pre></div>
</li>
<li>
<p>Windows: open a command prompt and run the following command:</p>
<div class="highlight highlight-source-postscript"><pre><span class="pl-smi">py</span> <span class="pl-c1">-3</span> <span class="pl-smi">--version</span></pre></div>
</li>
</ul>
<p>If the installation was successful, the output window should show the version of Python that you installed.</p>
<blockquote>
<p><strong>Note</strong> You can use the <code>py -0</code> command in the VS Code integrated terminal to view the versions of python installed on your machine. The default interpreter is identified by an asterisk (*).</p>
</blockquote>
<h2><a id="user-content-start-vs-code-in-a-project-workspace-folder" class="anchor" aria-hidden="true" href="#start-vs-code-in-a-project-workspace-folder"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Start VS Code in a project (workspace) folder</h2>
<p>At a command prompt or terminal, create an empty folder called "hello", navigate into it, and open VS Code (<code>code</code>) in that folder (<code>.</code>) by entering the following commands:</p>
<div class="highlight highlight-source-shell"><pre>mkdir hello
<span class="pl-c1">cd</span> hello
code <span class="pl-c1">.</span></pre></div>
<blockquote>
<p><strong>Note</strong>: If you're using an Anaconda distribution, be sure to use an Anaconda command prompt.</p>
</blockquote>
<p>By starting VS Code in a folder, that folder becomes your "workspace". VS Code stores settings that are specific to that workspace in <code>.vscode/settings.json</code>, which are separate from user settings that are stored globally.</p>
<p>Alternately, you can run VS Code through the operating system UI, then use <strong>File &gt; Open Folder</strong> to open the project folder.</p>
<h2><a id="user-content-select-a-python-interpreter" class="anchor" aria-hidden="true" href="#select-a-python-interpreter"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Select a Python interpreter</h2>
<p>Python is an interpreted language, and in order to run Python code and get Python IntelliSense, you must tell VS Code which interpreter to use.</p>
<p>From within VS Code, select a Python 3 interpreter by opening the <strong>Command Palette</strong> (<code>kb(workbench.action.showCommands)</code>), start typing the <strong>Python: Select Interpreter</strong> command to search, then select the command. You can also use the <strong>Select Python Environment</strong> option on the Status Bar if available (it may already show a selected interpreter, too):</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/environments/no-interpreter-selected-statusbar.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/environments/no-interpreter-selected-statusbar.png" alt="No interpreter selected" style="max-width:100%;"></a></p>
<p>The command presents a list of available interpreters that VS Code can find automatically, including virtual environments. If you don't see the desired interpreter, see <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/environments.md">Configuring Python environments</a>.</p>
<blockquote>
<p><strong>Note</strong>: When using an Anaconda distribution, the correct interpreter should have the suffix <code>('base':conda)</code>, for example <code>Python 3.7.3 64-bit ('base':conda)</code>.</p>
</blockquote>
<p>Selecting an interpreter sets the <code>python.pythonPath</code> value in your workspace settings to the path of the interpreter. To see the setting, select <strong>File</strong> &gt; <strong>Preferences</strong> &gt; <strong>Settings</strong> (<strong>Code</strong> &gt; <strong>Preferences</strong> &gt; <strong>Settings</strong> on macOS), then select the <strong>Workspace Settings</strong> tab.</p>
<blockquote>
<p><strong>Note</strong>: If you select an interpreter without a workspace folder open, VS Code sets <code>python.pythonPath</code> in your user settings instead, which sets the default interpreter for VS Code in general. The user setting makes sure you always have a default interpreter for Python projects. The workspace settings lets you override the user setting.</p>
</blockquote>
<h2><a id="user-content-create-a-python-hello-world-source-code-file" class="anchor" aria-hidden="true" href="#create-a-python-hello-world-source-code-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Create a Python Hello World source code file</h2>
<p>From the File Explorer toolbar, select the <strong>New File</strong> button on the <code>hello</code> folder:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/toolbar-new-file.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/toolbar-new-file.png" alt="File Explorer New File" style="max-width:100%;"></a></p>
<p>Name the file <code>hello.py</code>, and it automatically opens in the editor:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/hello-py-file-created.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/hello-py-file-created.png" alt="File Explorer hello.py" style="max-width:100%;"></a></p>
<p>By using the <code>.py</code> file extension, you tell VS Code to interpret this file as a Python program, so that it evaluates the contents with the Python extension and the selected interpreter.</p>
<blockquote>
<p><strong>Note</strong>: The File Explorer toolbar also allows you to create folders within your workspace to better organize your code. You can use the <strong>New folder</strong> button to quickly create a folder.</p>
</blockquote>
<p>Now that you have a code file in your Workspace, enter the following source code in <code>hello.py</code>:</p>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">msg</span> <span class="pl-c1">=</span> <span class="pl-s">"Hello World"</span>
<span class="pl-en">print</span>(<span class="pl-s1">msg</span>)</pre></div>
<p>When you start typing <code>print</code>, notice how <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/editor/intellisense.md">IntelliSense</a> presents auto-completion options.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/intellisense01.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/intellisense01.png" alt="IntelliSense appearing for Python code" style="max-width:100%;"></a></p>
<p>IntelliSense and auto-completions work for standard Python modules as well as other packages you've installed into the environment of the selected Python interpreter. It also provides completions for methods available on object types. For example, because the <code>msg</code> variable contains a string, IntelliSense provides string methods when you type <code>msg.</code>:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/intellisense02.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/intellisense02.png" alt="IntelliSense appearing for a variable whose type provides methods" style="max-width:100%;"></a></p>
<p>Feel free to experiment with IntelliSense some more, but then revert your changes so you have only the <code>msg</code> variable and the <code>print</code> call, and save the file (<code>kb(workbench.action.files.save)</code>).</p>
<p>For full details on editing, formatting, and refactoring, see <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/editing.md">Editing code</a>. The Python extension also has full support for <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/linting.md">Linting</a>.</p>
<h2><a id="user-content-run-hello-world" class="anchor" aria-hidden="true" href="#run-hello-world"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Run Hello World</h2>
<p>It's simple to run <code>hello.py</code> with Python. Just click the <strong>Run Python File in Terminal</strong> play button in the top-right side of the editor.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/run-python-file-in-terminal-button.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/run-python-file-in-terminal-button.png" alt="Run python file in terminal button" style="max-width:100%;"></a></p>
<p>The button opens a terminal panel in which your Python interpreter is automatically activated, then runs <code>python3 hello.py</code> (macOS/Linux) or <code>python hello.py</code> (Windows):</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/output-in-terminal.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/output-in-terminal.png" alt="Program output in a Python terminal" style="max-width:100%;"></a></p>
<p>There are three other ways you can run Python within VS Code:</p>
<ul>
<li>
<p>Right-click anywhere in the editor window and select <strong>Run Python File in Terminal</strong> (which saves the file automatically):</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/run-python-file-in-terminal.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/run-python-file-in-terminal.png" alt="Run Python File in Terminal command in the Python editor" style="max-width:100%;"></a></p>
</li>
<li>
<p>Select one or more lines, then press <code>kbstyle(Shift+Enter)</code> or right-click and select <strong>Run Selection/Line in Python Terminal</strong>. This command is convenient for testing just a part of a file.</p>
</li>
<li>
<p>From the Command Palette (<code>kb(workbench.action.showCommands)</code>), select the <strong>Python: Start REPL</strong> command to open a REPL terminal for the currently selected Python interpreter. In the REPL, you can then enter and run lines of code one at a time.</p>
</li>
</ul>
<h2><a id="user-content-configure-and-run-the-debugger" class="anchor" aria-hidden="true" href="#configure-and-run-the-debugger"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Configure and run the debugger</h2>
<p>Let's now try debugging our simple Hello World program.</p>
<p>First, set a breakpoint on line 2 of <code>hello.py</code> by placing the cursor on the <code>print</code> call and pressing <code>kb(editor.debug.action.toggleBreakpoint)</code>. Alternately, just click in the editor's left gutter, next to the line numbers. When you set a breakpoint, a red circle appears in the gutter.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/breakpoint-set.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/breakpoint-set.png" alt="Setting a breakpoint in hello.py" style="max-width:100%;"></a></p>
<p>Next, to initialize the debugger, press <code>kb(workbench.action.debug.start)</code>. Since this is your first time debugging this file, a configuration menu will open from the Command Palette allowing you to select the type of debug configuration you would like for the opened file.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/debug-configurations.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/debug-configurations.png" alt="Debug configurations after launch.json is created" style="max-width:100%;"></a></p>
<p><strong>Note</strong>: VS Code uses JSON files for all of its various configurations; <code>launch.json</code> is the standard name for a file containing debugging configurations.</p>
<p>These different configurations are fully explained in <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/debugging.md">Debugging configurations</a>; for now, just select <strong>Python File</strong>, which is the configuration that runs the current file shown in the editor using the currently selected Python interpreter.</p>
<p>The debugger will stop at the first line of the file breakpoint. The current line is indicated with a yellow arrow in the left margin. If you examine the <strong>Local</strong> variables window at this point, you will see now defined <code>msg</code> variable appears in the <strong>Local</strong> pane.</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/debug-step-02.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/debug-step-02.png" alt="Debugging step 2 - variable defined" style="max-width:100%;"></a></p>
<p>A debug toolbar appears along the top with the following commands from left to right: continue (<code>kb(workbench.action.debug.start)</code>), step over (<code>kb(workbench.action.debug.stepOver)</code>), step into (<code>kb(workbench.action.debug.stepInto)</code>), step out (<code>kb(workbench.action.debug.stepOut)</code>), restart (<code>kb(workbench.action.debug.restart)</code>), and stop (<code>kb(workbench.action.debug.stop)</code>).</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/debug-toolbar.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/debug-toolbar.png" alt="Debugging toolbar" style="max-width:100%;"></a></p>
<p>The Status Bar also changes color (orange in many themes) to indicate that you're in debug mode. The <strong>Python Debug Console</strong> also appears automatically in the lower right panel to show the commands being run, along with the program output.</p>
<p>To continue running the program, select the continue command on the debug toolbar (<code>kb(workbench.action.debug.start)</code>). The debugger runs the program to the end.</p>
<blockquote>
<p><strong>Tip</strong> Debugging information can also be seen by hovering over code, such as variables. In the case of <code>msg</code>, hovering over the variable will display the string <code>Hello world</code> in a box above the variable.</p>
</blockquote>
<p>You can also work with variables in the <strong>Debug Console</strong> (If you don't see it, select <strong>Debug Console</strong> in the lower right area of VS Code, or select it from the <strong>...</strong> menu.) Then try entering the following lines, one by one, at the <strong>&gt;</strong> prompt at the bottom of the console:</p>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">msg</span>
<span class="pl-s1">msg</span>.<span class="pl-en">capitalize</span>()
<span class="pl-s1">msg</span>.<span class="pl-en">split</span>()</pre></div>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/debug-step-03.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/debug-step-03.png" alt="Debugging step 3 - using the debug console" style="max-width:100%;"></a></p>
<p>Select the blue <strong>Continue</strong> button on the toolbar again (or press F5) to run the program to completion. "Hello World" appears in the <strong>Python Debug Console</strong> if you switch back to it, and VS Code exits debugging mode once the program is complete.</p>
<p>If you restart the debugger, the debugger again stops on the first breakpoint.</p>
<p>To stop running a program before it's complete, use the red square stop button on the debug toolbar (<code>kb(workbench.action.debug.stop)</code>), or use the <strong>Debug &gt; Stop debugging</strong> menu command.</p>
<p>For full details, see <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/debugging.md">Debugging configurations</a>, which includes notes on how to use a specific Python interpreter for debugging.</p>
<blockquote>
<p><strong>Tip: Use Logpoints instead of print statements</strong>: Developers often litter source code with <code>print</code> statements to quickly inspect variables without necessarily stepping through each line of code in a debugger. In VS Code, you can instead use <strong>Logpoints</strong>. A Logpoint is like a breakpoint except that it logs a message to the console and doesn't stop the program. For more information, see <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/editor/debugging.md#logpoints">Logpoints</a> in the main VS Code debugging article.</p>
</blockquote>
<h2><a id="user-content-install-and-use-packages" class="anchor" aria-hidden="true" href="#install-and-use-packages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Install and use packages</h2>
<p>Let's now run an example that's a little more interesting. In Python, packages are how you obtain any number of useful code libraries, typically from <a href="https://pypi.org/" rel="nofollow">PyPI</a>. For this example, you use the <code>matplotlib</code> and <code>numpy</code> packages to create a graphical plot as is commonly done with data science. (Note that <code>matplotlib</code> cannot show graphs when running in the <a href="https://docs.microsoft.com/windows/wsl/about" rel="nofollow">Windows Subsystem for Linux</a> as it lacks the necessary UI support.)</p>
<p>Return to the <strong>Explorer</strong> view (the top-most icon on the left side, which shows files), create a new file called <code>standardplot.py</code>, and paste in the following source code:</p>
<div class="highlight highlight-source-python"><pre><span class="pl-k">import</span> <span class="pl-s1">matplotlib</span>.<span class="pl-s1">pyplot</span> <span class="pl-k">as</span> <span class="pl-s1">plt</span>
<span class="pl-k">import</span> <span class="pl-s1">numpy</span> <span class="pl-k">as</span> <span class="pl-s1">np</span>

<span class="pl-s1">x</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">linspace</span>(<span class="pl-c1">0</span>, <span class="pl-c1">20</span>, <span class="pl-c1">100</span>)  <span class="pl-c"># Create a list of evenly-spaced numbers over the range</span>
<span class="pl-s1">plt</span>.<span class="pl-en">plot</span>(<span class="pl-s1">x</span>, <span class="pl-s1">np</span>.<span class="pl-en">sin</span>(<span class="pl-s1">x</span>))       <span class="pl-c"># Plot the sine of each x point</span>
<span class="pl-s1">plt</span>.<span class="pl-en">show</span>()                   <span class="pl-c"># Display the plot</span></pre></div>
<blockquote>
<p><strong>Tip</strong>: If you enter the above code by hand, you may find that auto-completions change the names after the <code>as</code> keywords when you press <code>kbstyle(Enter)</code> at the end of a line. To avoid this, type a space, then <code>kbstyle(Enter)</code>.</p>
</blockquote>
<p>Next, try running the file in the debugger using the "Python: Current file" configuration as described in the last section.</p>
<p>Unless you're using an Anaconda distribution or have previously installed the <code>matplotlib</code> package, you should see the message, <strong>"ModuleNotFoundError: No module named 'matplotlib'"</strong>. Such a message indicates that the required package isn't available in your system.</p>
<p>To install the <code>matplotlib</code> package (which also installs <code>numpy</code> as a dependency), stop the debugger and use the Command Palette to run <strong>Terminal: Create New Integrated Terminal</strong> (<code>kb(workbench.action.terminal.new)</code>)). This command opens a command prompt for your selected interpreter.</p>
<p>A best practice among Python developers is to avoid installing packages into a global interpreter environment. You instead use a project-specific <code>virtual environment</code> that contains a copy of a global interpreter. Once you activate that environment, any packages you then install are isolated from other environments. Such isolation reduces many complications that can arise from conflicting package versions. To create a <em>virtual environment</em> and install the required packages, enter the following commands as appropriate for your operating system:</p>
<blockquote>
<p><strong>Note</strong>: For additional information about virtual environments, see <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/environments.md#global-virtual-and-conda-environments">Environments</a>.</p>
</blockquote>
<ol>
<li>
<p>Create and activate the virtual environment</p>
<blockquote>
<p><strong>Note</strong>: When you create a new virtual environment, you should be prompted by VS  Code to set it as the default for your workspace folder. If selected, the environment will automatically be activated when you open a new terminal.</p>
</blockquote>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/virtual-env-dialog.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/virtual-env-dialog.png" alt="Virtual environment dialog" style="max-width:100%;"></a></p>
<p><strong>For windows</strong></p>
<div class="highlight highlight-source-batchfile"><pre>py <span class="pl-c1">-3</span> -m venv .venv
.venv\scripts\activate</pre></div>
<p>If the activate command generates the message "Activate.ps1 is not digitally signed. You cannot run this script on the
current system.", then you need to temporarily change the PowerShell execution policy to allow scripts to
run (see <a href="https://go.microsoft.com/fwlink/?LinkID=135170" rel="nofollow">About Execution Policies</a> in the PowerShell documentation):</p>
<div class="highlight highlight-source-batchfile"><pre>Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process</pre></div>
<p><strong>For macOS/Linux</strong></p>
<div class="highlight highlight-source-shell"><pre>python3 -m venv .venv
<span class="pl-c1">source</span> .venv/bin/activate</pre></div>
</li>
<li>
<p>Select your new environment by using the <strong>Python: Select Interpreter</strong> command from the <strong>Command Palette</strong>.</p>
</li>
<li>
<p>Install the packages</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> Don't use with Anaconda distributions because they include matplotlib already.</span>

<span class="pl-c"><span class="pl-c">#</span> macOS</span>
python3 -m pip install matplotlib

<span class="pl-c"><span class="pl-c">#</span> Windows (may require elevation)</span>
python -m pip install matplotlib

<span class="pl-c"><span class="pl-c">#</span> Linux (Debian)</span>
apt-get install python3-tk
python3 -m pip install matplotlib</pre></div>
</li>
<li>
<p>Rerun the program now (with or without the debugger) and after a few moments a plot window appears with the output:</p>
<p><a target="_blank" rel="noopener noreferrer" href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/images/tutorial/plot-output.png"><img src="/Yuichi-Ikeda/vscode-docs/raw/master/docs/python/images/tutorial/plot-output.png" alt="matplotlib output" style="max-width:100%;"></a></p>
</li>
<li>
<p>Once you are finished, type <code>deactivate</code> in the terminal window to deactivate the virtual environment.</p>
</li>
</ol>
<p>For additional examples of creating and activating a virtual environment and installing packages, see the <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/tutorial-django.md">Django tutorial</a> and the <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/tutorial-flask.md">Flask tutorial</a>.</p>
<h2><a id="user-content-next-steps" class="anchor" aria-hidden="true" href="#next-steps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Next steps</h2>
<p>You can configure VS Code to use any Python environment you have installed, including virtual and conda environments. You can also use a separate environment for debugging. For full details, see <a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/environments.md">Environments</a>.</p>
<p>To learn more about the Python language, follow any of the <a href="https://wiki.python.org/moin/BeginnersGuide/Programmers" rel="nofollow">programming tutorials</a> listed on python.org within the context of VS Code.</p>
<p>To learn to build web apps with the Django and Flask frameworks, see the following tutorials:</p>
<ul>
<li><a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/tutorial-django.md">Use Django in Visual Studio Code</a></li>
<li><a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/tutorial-flask.md">Use Flask in Visual Studio Code</a></li>
</ul>
<p>There is then much more to explore with Python in Visual Studio Code:</p>
<ul>
<li><a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/editing.md">Editing code</a> - Learn about autocomplete, IntelliSense, formatting, and refactoring for Python.</li>
<li><a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/linting.md">Linting</a> - Enable, configure, and apply a variety of Python linters.</li>
<li><a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/debugging.md">Debugging</a> - Learn to debug Python both locally and remotely.</li>
<li><a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/testing.md">Testing</a> - Configure test environments and discover, run, and debug tests.</li>
<li><a href="/Yuichi-Ikeda/vscode-docs/blob/master/docs/python/settings-reference.md">Settings reference</a> - Explore the full range of Python-related settings in VS Code.</li>
<li><a href="https://docs.microsoft.com/azure/python/tutorial-deploy-containers-01" rel="nofollow">Deploy Python to Azure App Service using containers</a></li>
<li><a href="https://docs.microsoft.com/azure/python/tutorial-deploy-app-service-on-linux-01" rel="nofollow">Deploy Python to Azure App Service on Linux</a></li>
</ul>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2020 GitHub, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-yUQVJlf6PdPtYetPr+JKEF64/1izvT1er3NK9Fs/+377lvW6/xA8CNRyJWRbghnICzO9pz593eAXT/D+a+Ec2w==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-c9441526.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-BjxkrrB8TxyhuZdZXxS32+MYqabW7hDE/erry2+ViUbGzDWmyjWhcx2xTsogLBEpoPYV6hlYCK9WCZRZk1GEmQ==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-063c64ae.js"></script>
    
    
    
  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  
  <div class="js-notification-shelf-not-found-error" hidden></div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

