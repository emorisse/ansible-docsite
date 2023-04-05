<!DOCTYPE html>

<html>
<head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Red Hat Ansible Automation Controller Docs -- Translations: Korean</title>
    <meta name="description" content="Red Hat Ansible Automation Controller Docs - Translations: Japanese, Korean, and Simplified Chinese">
    <meta name="author" content="Ansible, Inc.">
    <link href="https://static.redhat.com/libs/redhat/redhat-font/2.0.0/webfonts/red-hat-font.css" rel="stylesheet">
    <link rel="stylesheet" href="https://www.ansible.com/hubfs/css/styles.min.css" />

    <!-- <script>
      (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
      (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
      m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
      })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

      ga('create', 'UA-29861888-3', 'auto');
      ga('send', 'pageview');

    </script> -->

    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" crossorigin="anonymous"></script>
    <script src="https://www.ansible.com/hubfs/js/scripts.min.js"></script>
    <script src="//www.redhat.com/dtm.js"></script>
</head>

<style>
/* Resources section: change "display: block" to "display: none" to hide */
.resources {
    display: none;
}

body, html {
    color: #333;
    font-weight: 300;
    font-family: RedHatText,"Red Hat Text",Overpass,"Helvetica Neue",Arial,sans-serif;
}

nav {
    background: #151515;
    color: #fff;
    font-size: 1.25rem;
}

nav .main-logo-link {
    color: #fff;
}

nav .navbar-toggler{
    color: #fff;
    outline: none;
}

nav .navbar-toggler .icon-bar {
    display: block;
    width: 1.375rem;
    height: 0.125rem;
    border-radius: 1px;
    background-color: #fff;
    transition: all 300ms ease-in-out;
    transform: rotate(0);
    opacity: 1;
    margin-top: 0.3125rem;
}

nav .navbar-toggler .icon-bar.top {
    margin-top: 0.625rem;
    transform: rotate(45deg);
}

nav .navbar-toggler .icon-bar.center {
    opacity: 0;
}

nav .navbar-toggler .icon-bar.bottom {
    margin-top: -0.5rem;
    transform: rotate(-45deg);
}

nav .navbar-toggler.collapsed .icon-bar {
    transform: rotate(0);
    opacity: 1;
    margin-top: 0.5rem;
}

nav .nav-link {
    color: #fff;
    font-size: 1rem;
}

h1, h2, h3, h4, h5, h6 {
    font-family: RedHatDisplay, "Red Hat Display", Overpass,"Helvetica Neue",Arial,sans-serif;
}

h1 {
    font-size: 2.5rem;
}

h2 {
    font-size: 2.25rem;
}

h4 {
    font-size: 1.5rem;
    margin-bottom: 1.2rem;
}

.subhead {
    font-size: 1.5rem;
    font-family: RedHatDisplay, "Red Hat Display", Overpass,"Helvetica Neue",Arial,sans-serif;
}

.card.border {
    border-color: #d2d2d2 !important;
}

.cards .row [class*="col-"] {
    display: flex;
}

.cards .card {
    flex: 1;
}

.cards a {
    color: #333;
    display: flex;
    flex: 1;
}

.cards a:hover .card {
    background: #f2f2f2;
    transition: all 300ms ease-in-out;
}

.cards a:hover h4 {
    text-decoration: underline;
}

.cards .btn {
    cursor: pointer;
    display: inline-block;
}

.cards .btn:hover {
    color: #fff !important;
}

.resources {
    background: #F2F2F2;
}

.resources .card {
    background-color: #fff;
}

.resources a {
    font-size: 1.125rem;
}

.footer iframe {
    width: 100%;
    height: 800px;
    border: 0px;
}

@media (min-width: 768px){
    nav.main .navbar-nav .nav-link {
        padding-right: .75rem;
        padding-left: .75rem;
    }
}

</style>

<body>

    <!-- BEGIN NAVIGATION -->
    <nav class="navbar navbar-expand-md p-1">
        <div class="container">
            <a href="/" class="main-logo-link">
                <span class="navbar-brand d-flex justify-content-center">
                    <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" width="28" height="28" viewBox="0 0 28 28" style="enable-background:new 0 0 28 28;" xml:space="preserve" class="mr-1">
                    <style type="text/css"> .ansHeader{fill:#FFFFFF;} </style>
                    <circle class="ansHeader" cx="14" cy="14" r="13.5"/>
                    <path d="M20.4,19.3L15,6.4c-0.2-0.4-0.5-0.6-0.8-0.6c-0.4,0-0.7,0.2-0.9,0.6L7.5,20.6h2l2.3-5.8l7,5.6c0.3,0.2,0.5,0.3,0.7,0.3c0.5,0,1-0.4,1-1C20.5,19.6,20.4,19.5,20.4,19.3z M14.2,8.7l3.5,8.6l-5.3-4.1L14.2,8.7z"/>
                    </svg>
                    <p class="m-0">Documentation</p>
                </span>
            </a>

            <button class="navbar-toggler collapsed" type="button" data-toggle="collapse" data-target="#main-menu" aria-controls="main-menu" aria-expanded="false" aria-label="Toggle navigation">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar top"></span>
                <span class="icon-bar center"></span>
                <span class="icon-bar bottom"></span>
            </button>

            <div class="collapse navbar-collapse" id="main-menu">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="https://www.ansible.com/products/automation-platform">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://www.ansible.com/blog">Blog</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://www.ansible.com/community">Community</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://www.ansible.com/resources/webinars-training">Webinars &amp; Training</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://www.redhat.com/en/technologies/management/ansible/try-it">Free trial</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- END NAVIGATION -->

    <!-- BEGIN PAGE TITLE -->
    <header class="headline py-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col text-center">
                    <img src="https://static.redhat.com/libs/redhat/brand-assets/2/corp/logo--400.png" class="mb-3">
                    <h1 class="mb-2">Automation Controller Docs</h1>
                    <p class="subhead">automation controller -- Translations: Korean (한국어 문서)</p>
                </div>
            </div>
        </div>

        <div class="container">
            <div class="row">
                <ul class="nav subnav">
                    <li class="nav-item">
                        <a class="nav-link" href="#4.3.0">4.3.0</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#4.2.1">4.2.1</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#4.2.0">4.2.0</a>
                    </li>
                </ul>
            </div>
        </div>

    </header>
    <!-- END PAGE TITLE -->

<!-- Begin version 4.3.0 -->
    <header class="headline py-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col text-center">
                    <a id="4.3.0">
                    <p class="subhead">automation controller 4.3.0</p>
                    </a>
                </div>
            </div>
        </div>
    </header>
    <!-- End version 4.3.0 -->

    <!-- BEGIN MAIN CARDS for Korean 4.3.0 -->
    <section class="cards pt-0">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/quickstart">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 퀵스타트 가이드 <br/>version 4.3.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/quickstart" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/release-notes/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 릴리스  노트 <br/>version 4.3.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/release-notes/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/controllerapi/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller API 가이드  <br/>version 4.3.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/controllerapi/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/administration/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 관리 가이드 <br/>version 4.3.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/administration/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/userguide/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 사용자 가이드 <br/>version 4.3.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/userguide/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/upgrade-migration-guide/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 업그레이드 마이그레이션 가이드 <br/>version 4.3.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.3.0/html_ko/upgrade-migration-guide/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
</div></div></section>

<!-- Begin version 4.2.1 -->
    <header class="headline py-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col text-center">
                    <a id="4.2.1">
                    <p class="subhead">automation controller 4.2.1</p>
                    </a>
                </div>
            </div>
        </div>
    </header>
    <!-- End version 4.2.1 -->

    <!-- BEGIN MAIN CARDS for Korean 4.2.1 -->
    <section class="cards pt-0">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/quickstart">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 퀵스타트 가이드 <br/>version 4.2.1</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/quickstart" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/release-notes/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 릴리스  노트 <br/>version 4.2.1</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/release-notes/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/controllerapi/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller API 가이드  <br/>version 4.2.1</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/controllerapi/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/administration/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 관리 가이드 <br/>version 4.2.1</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/administration/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/userguide/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 사용자 가이드 <br/>version 4.2.1</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/userguide/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/upgrade-migration-guide/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 업그레이드 마이그레이션 가이드 <br/>version 4.2.1</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.1/html_ko/upgrade-migration-guide/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
</div></div></section>


<!-- Begin version 4.2.0 -->
    <header class="headline py-5">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col text-center">
                    <a id="4.2.0">
                    <p class="subhead">automation controller 4.2.0</p>
                    </a>
                </div>
            </div>
        </div>
    </header>
    <!-- End version 4.2.0 -->

    <!-- BEGIN MAIN CARDS for Korean 4.2.0 -->
    <section class="cards pt-0">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/quickstart">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 퀵스타트 가이드 <br/>version 4.2.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/quickstart" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/release-notes/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 릴리스  노트 <br/>version 4.2.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/release-notes/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/controllerapi/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller API 가이드  <br/>version 4.2.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/controllerapi/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/administration/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 관리 가이드 <br/>version 4.2.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/administration/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/userguide/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 사용자 가이드 <br/>version 4.2.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/userguide/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-md-6 col-lg-4">
                    <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/upgrade-migration-guide/">
                        <div class="card border">
                            <div class="card-body">
                                <h4 class="card-title">Korean: automation controller 업그레이드 마이그레이션 가이드 <br/>version 4.2.0</h4>
                            </div>
                             <div class="card-footer">
                            <a href="http://docs.ansible.com/automation-controller/4.2.0/html_ko/upgrade-migration-guide/" class="btn btn-outline-black">Supported</a>
                            </div>
                        </div>
                    </a>
                </div>
</div></div></section>


<!-- ***************************************************************************************************************************************************************************************************************************************************************************************************** -->


    <!-- BEGIN RESOURCES SECTION - SEE .resources CSS RULE TO TOGGLE OFF -->
    <section class="resources pt-4">
        <div class="container">
            <div class="row justify-content-center pb-3">
                <div class="col col-lg-9 col-xl-7 text-center">
                    <h2 class="mb-2">Additional Resources</h2>
                    <p class="subhead">Vivamus magna justo, lacinia eget&nbsp;consectetur</p>
                </div>
            </div>
            <div class="row">
                <!-- BEGIN RESOURCE BLOCK 1 -->
                <div class="col-md-4 d-flex">
                    <div class="card border">
                        <div class="card-body">
                            <h4 class="card-title">Headline</h4>
                            <a href="#" class="d-inline-block pb-2 border-bottom">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                            <a href="#" class="d-inline-block py-2 border-bottom">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                            <a href="#" class="d-inline-block pt-2">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                          </div>
                    </div>
                </div>
                <!-- BEGIN RESOURCE BLOCK 2 -->
                <div class="col-md-4 d-flex">
                    <div class="card border">
                        <div class="card-body">
                            <h4 class="card-title">Headline</h4>
                            <a href="#" class="d-inline-block pb-2 border-bottom">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                            <a href="#" class="d-inline-block py-2 border-bottom">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                            <a href="#" class="d-inline-block pt-2">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                          </div>
                    </div>
                </div>
                <!-- BEGIN RESOURCE BLOCK 3 -->
                <div class="col-md-4 d-flex">
                    <div class="card border">
                        <div class="card-body">
                            <h4 class="card-title">Headline</h4>
                            <a href="#" class="d-inline-block pb-2 border-bottom">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                            <a href="#" class="d-inline-block py-2 border-bottom">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                            <a href="#" class="d-inline-block pt-2">
                                Lorem ipsum dolor sit amet consectetur adipiscing elit in sit...
                            </a>
                          </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- END RESOURCES SECTION - SEE '.resources' CSS RULE TO TOGGLE OFF -->

    <!-- BEGIN FOOTER -->
    <section class="footer py-0">
        <iframe src="https://www.ansible.com/docs-footer" scrolling="no"></iframe>
    </section>

    <script>
    /*! iFrame Resizer (iframeSizer.min.js ) - v3.5.16 - 2018-01-21
    *  Desc: Force cross domain iframes to size to content.
    *  Requires: iframeResizer.contentWindow.min.js to be loaded into the target frame.
    *  Copyright: (c) 2018 David J. Bradshaw - dave@bradshaw.net
    *  License: MIT
    */

    !function(a){"use strict";function b(a,b,c){"addEventListener"in window?a.addEventListener(b,c,!1):"attachEvent"in window&&a.attachEvent("on"+b,c)}function c(a,b,c){"removeEventListener"in window?a.removeEventListener(b,c,!1):"detachEvent"in window&&a.detachEvent("on"+b,c)}function d(){var a,b=["moz","webkit","o","ms"];for(a=0;a<b.length&&!N;a+=1)N=window[b[a]+"RequestAnimationFrame"];N||h("setup","RequestAnimationFrame not supported")}function e(a){var b="Host page: "+a;return window.top!==window.self&&(b=window.parentIFrame&&window.parentIFrame.getId?window.parentIFrame.getId()+": "+a:"Nested host page: "+a),b}function f(a){return K+"["+e(a)+"]"}function g(a){return P[a]?P[a].log:G}function h(a,b){k("log",a,b,g(a))}function i(a,b){k("info",a,b,g(a))}function j(a,b){k("warn",a,b,!0)}function k(a,b,c,d){!0===d&&"object"==typeof window.console&&console[a](f(b),c)}function l(a){function d(){function a(){s(U),p(V),I("resizedCallback",U)}f("Height"),f("Width"),t(a,U,"init")}function e(){var a=T.substr(L).split(":");return{iframe:P[a[0]]&&P[a[0]].iframe,id:a[0],height:a[1],width:a[2],type:a[3]}}function f(a){var b=Number(P[V]["max"+a]),c=Number(P[V]["min"+a]),d=a.toLowerCase(),e=Number(U[d]);h(V,"Checking "+d+" is in range "+c+"-"+b),c>e&&(e=c,h(V,"Set "+d+" to min value")),e>b&&(e=b,h(V,"Set "+d+" to max value")),U[d]=""+e}function g(){function b(){function a(){var a=0,b=!1;for(h(V,"Checking connection is from allowed list of origins: "+d);a<d.length;a++)if(d[a]===c){b=!0;break}return b}function b(){var a=P[V]&&P[V].remoteHost;return h(V,"Checking connection is from: "+a),c===a}return d.constructor===Array?a():b()}var c=a.origin,d=P[V]&&P[V].checkOrigin;if(d&&""+c!="null"&&!b())throw new Error("Unexpected message received from: "+c+" for "+U.iframe.id+". Message was: "+a.data+". This error can be disabled by setting the checkOrigin: false option or by providing of array of trusted domains.");return!0}function k(){return K===(""+T).substr(0,L)&&T.substr(L).split(":")[0]in P}function l(){var a=U.type in{"true":1,"false":1,undefined:1};return a&&h(V,"Ignoring init message from meta parent page"),a}function w(a){return T.substr(T.indexOf(":")+J+a)}function y(a){h(V,"MessageCallback passed: {iframe: "+U.iframe.id+", message: "+a+"}"),I("messageCallback",{iframe:U.iframe,message:JSON.parse(a)}),h(V,"--")}function z(){var a=document.body.getBoundingClientRect(),b=U.iframe.getBoundingClientRect();return JSON.stringify({iframeHeight:b.height,iframeWidth:b.width,clientHeight:Math.max(document.documentElement.clientHeight,window.innerHeight||0),clientWidth:Math.max(document.documentElement.clientWidth,window.innerWidth||0),offsetTop:parseInt(b.top-a.top,10),offsetLeft:parseInt(b.left-a.left,10),scrollTop:window.pageYOffset,scrollLeft:window.pageXOffset})}function A(a,b){function c(){u("Send Page Info","pageInfo:"+z(),a,b)}x(c,32)}function B(){function a(a,b){function c(){P[f]?A(P[f].iframe,f):d()}["scroll","resize"].forEach(function(d){h(f,a+d+" listener for sendPageInfo"),b(window,d,c)})}function d(){a("Remove ",c)}function e(){a("Add ",b)}var f=V;e(),P[f]&&(P[f].stopPageInfo=d)}function C(){P[V]&&P[V].stopPageInfo&&(P[V].stopPageInfo(),delete P[V].stopPageInfo)}function D(){var a=!0;return null===U.iframe&&(j(V,"IFrame ("+U.id+") not found"),a=!1),a}function E(a){var b=a.getBoundingClientRect();return o(V),{x:Math.floor(Number(b.left)+Number(M.x)),y:Math.floor(Number(b.top)+Number(M.y))}}function F(a){function b(){M=f,G(),h(V,"--")}function c(){return{x:Number(U.width)+e.x,y:Number(U.height)+e.y}}function d(){window.parentIFrame?window.parentIFrame["scrollTo"+(a?"Offset":"")](f.x,f.y):j(V,"Unable to scroll to requested position, window.parentIFrame not found")}var e=a?E(U.iframe):{x:0,y:0},f=c();h(V,"Reposition requested from iFrame (offset x:"+e.x+" y:"+e.y+")"),window.top!==window.self?d():b()}function G(){!1!==I("scrollCallback",M)?p(V):q()}function H(a){function b(){var a=E(f);h(V,"Moving to in page link (#"+d+") at x: "+a.x+" y: "+a.y),M={x:a.x,y:a.y},G(),h(V,"--")}function c(){window.parentIFrame?window.parentIFrame.moveToAnchor(d):h(V,"In page link #"+d+" not found and window.parentIFrame not found")}var d=a.split("#")[1]||"",e=decodeURIComponent(d),f=document.getElementById(e)||document.getElementsByName(e)[0];f?b():window.top!==window.self?c():h(V,"In page link #"+d+" not found")}function I(a,b){return m(V,a,b)}function N(){switch(P[V]&&P[V].firstRun&&S(),U.type){case"close":P[V].closeRequestCallback?m(V,"closeRequestCallback",P[V].iframe):n(U.iframe);break;case"message":y(w(6));break;case"scrollTo":F(!1);break;case"scrollToOffset":F(!0);break;case"pageInfo":A(P[V]&&P[V].iframe,V),B();break;case"pageInfoStop":C();break;case"inPageLink":H(w(9));break;case"reset":r(U);break;case"init":d(),I("initCallback",U.iframe);break;default:d()}}function O(a){var b=!0;return P[a]||(b=!1,j(U.type+" No settings for "+a+". Message was: "+T)),b}function Q(){for(var a in P)u("iFrame requested init",v(a),document.getElementById(a),a)}function S(){P[V]&&(P[V].firstRun=!1)}var T=a.data,U={},V=null;"[iFrameResizerChild]Ready"===T?Q():k()?(U=e(),V=R=U.id,P[V]&&(P[V].loaded=!0),!l()&&O(V)&&(h(V,"Received: "+T),D()&&g()&&N())):i(V,"Ignored: "+T)}function m(a,b,c){var d=null,e=null;if(P[a]){if(d=P[a][b],"function"!=typeof d)throw new TypeError(b+" on iFrame["+a+"] is not a function");e=d(c)}return e}function n(a){var b=a.id;h(b,"Removing iFrame: "+b),a.parentNode&&a.parentNode.removeChild(a),m(b,"closedCallback",b),h(b,"--"),delete P[b]}function o(b){null===M&&(M={x:window.pageXOffset!==a?window.pageXOffset:document.documentElement.scrollLeft,y:window.pageYOffset!==a?window.pageYOffset:document.documentElement.scrollTop},h(b,"Get page position: "+M.x+","+M.y))}function p(a){null!==M&&(window.scrollTo(M.x,M.y),h(a,"Set page position: "+M.x+","+M.y),q())}function q(){M=null}function r(a){function b(){s(a),u("reset","reset",a.iframe,a.id)}h(a.id,"Size reset requested by "+("init"===a.type?"host page":"iFrame")),o(a.id),t(b,a,"reset")}function s(a){function b(b){a.iframe.style[b]=a[b]+"px",h(a.id,"IFrame ("+e+") "+b+" set to "+a[b]+"px")}function c(b){H||"0"!==a[b]||(H=!0,h(e,"Hidden iFrame detected, creating visibility listener"),y())}function d(a){b(a),c(a)}var e=a.iframe.id;P[e]&&(P[e].sizeHeight&&d("height"),P[e].sizeWidth&&d("width"))}function t(a,b,c){c!==b.type&&N?(h(b.id,"Requesting animation frame"),N(a)):a()}function u(a,b,c,d,e){function f(){var e=P[d]&&P[d].targetOrigin;h(d,"["+a+"] Sending msg to iframe["+d+"] ("+b+") targetOrigin: "+e),c.contentWindow.postMessage(K+b,e)}function g(){j(d,"["+a+"] IFrame("+d+") not found")}function i(){c&&"contentWindow"in c&&null!==c.contentWindow?f():g()}function k(){function a(){!P[d]||P[d].loaded||l||(l=!0,j(d,"IFrame has not responded within "+P[d].warningTimeout/1e3+" seconds. Check iFrameResizer.contentWindow.js has been loaded in iFrame. This message can be ingored if everything is working, or you can set the warningTimeout option to a higher value or zero to suppress this warning."))}e&&P[d]&&P[d].warningTimeout&&(P[d].msgTimeout=setTimeout(a,P[d].warningTimeout))}var l=!1;d=d||c.id,P[d]&&(i(),k())}function v(a){return a+":"+P[a].bodyMarginV1+":"+P[a].sizeWidth+":"+P[a].log+":"+P[a].interval+":"+P[a].enablePublicMethods+":"+P[a].autoResize+":"+P[a].bodyMargin+":"+P[a].heightCalculationMethod+":"+P[a].bodyBackground+":"+P[a].bodyPadding+":"+P[a].tolerance+":"+P[a].inPageLinks+":"+P[a].resizeFrom+":"+P[a].widthCalculationMethod}function w(c,d){function e(){function a(a){1/0!==P[x][a]&&0!==P[x][a]&&(c.style[a]=P[x][a]+"px",h(x,"Set "+a+" = "+P[x][a]+"px"))}function b(a){if(P[x]["min"+a]>P[x]["max"+a])throw new Error("Value for min"+a+" can not be greater than max"+a)}b("Height"),b("Width"),a("maxHeight"),a("minHeight"),a("maxWidth"),a("minWidth")}function f(){var a=d&&d.id||S.id+F++;return null!==document.getElementById(a)&&(a+=F++),a}function g(a){return R=a,""===a&&(c.id=a=f(),G=(d||{}).log,R=a,h(a,"Added missing iframe ID: "+a+" ("+c.src+")")),a}function i(){switch(h(x,"IFrame scrolling "+(P[x]&&P[x].scrolling?"enabled":"disabled")+" for "+x),c.style.overflow=!1===(P[x]&&P[x].scrolling)?"hidden":"auto",P[x]&&P[x].scrolling){case!0:c.scrolling="yes";break;case!1:c.scrolling="no";break;default:c.scrolling=P[x]?P[x].scrolling:"no"}}function k(){("number"==typeof(P[x]&&P[x].bodyMargin)||"0"===(P[x]&&P[x].bodyMargin))&&(P[x].bodyMarginV1=P[x].bodyMargin,P[x].bodyMargin=""+P[x].bodyMargin+"px")}function l(){var a=P[x]&&P[x].firstRun,b=P[x]&&P[x].heightCalculationMethod in O;!a&&b&&r({iframe:c,height:0,width:0,type:"init"})}function m(){Function.prototype.bind&&P[x]&&(P[x].iframe.iFrameResizer={close:n.bind(null,P[x].iframe),resize:u.bind(null,"Window resize","resize",P[x].iframe),moveToAnchor:function(a){u("Move to anchor","moveToAnchor:"+a,P[x].iframe,x)},sendMessage:function(a){a=JSON.stringify(a),u("Send Message","message:"+a,P[x].iframe,x)}})}function o(d){function e(){u("iFrame.onload",d,c,a,!0),l()}b(c,"load",e),u("init",d,c,a,!0)}function p(a){if("object"!=typeof a)throw new TypeError("Options is not an object")}function q(a){for(var b in S)S.hasOwnProperty(b)&&(P[x][b]=a.hasOwnProperty(b)?a[b]:S[b])}function s(a){return""===a||"file://"===a?"*":a}function t(a){a=a||{},P[x]={firstRun:!0,iframe:c,remoteHost:c.src.split("/").slice(0,3).join("/")},p(a),q(a),P[x]&&(P[x].targetOrigin=!0===P[x].checkOrigin?s(P[x].remoteHost):"*")}function w(){return x in P&&"iFrameResizer"in c}var x=g(c.id);w()?j(x,"Ignored iFrame, already setup."):(t(d),i(),e(),k(),o(v(x)),m())}function x(a,b){null===Q&&(Q=setTimeout(function(){Q=null,a()},b))}function y(){function a(){function a(a){function b(b){return"0px"===(P[a]&&P[a].iframe.style[b])}function c(a){return null!==a.offsetParent}P[a]&&c(P[a].iframe)&&(b("height")||b("width"))&&u("Visibility change","resize",P[a].iframe,a)}for(var b in P)a(b)}function b(b){h("window","Mutation observed: "+b[0].target+" "+b[0].type),x(a,16)}function c(){var a=document.querySelector("body"),c={attributes:!0,attributeOldValue:!1,characterData:!0,characterDataOldValue:!1,childList:!0,subtree:!0},e=new d(b);e.observe(a,c)}var d=window.MutationObserver||window.WebKitMutationObserver;d&&c()}function z(a){function b(){B("Window "+a,"resize")}h("window","Trigger event: "+a),x(b,16)}function A(){function a(){B("Tab Visable","resize")}"hidden"!==document.visibilityState&&(h("document","Trigger event: Visiblity change"),x(a,16))}function B(a,b){function c(a){return P[a]&&"parent"===P[a].resizeFrom&&P[a].autoResize&&!P[a].firstRun}for(var d in P)c(d)&&u(a,b,document.getElementById(d),d)}function C(){b(window,"message",l),b(window,"resize",function(){z("resize")}),b(document,"visibilitychange",A),b(document,"-webkit-visibilitychange",A),b(window,"focusin",function(){z("focus")}),b(window,"focus",function(){z("focus")})}function D(){function b(a,b){function c(){if(!b.tagName)throw new TypeError("Object is not a valid DOM element");if("IFRAME"!==b.tagName.toUpperCase())throw new TypeError("Expected <IFRAME> tag, found <"+b.tagName+">")}b&&(c(),w(b,a),e.push(b))}function c(a){a&&a.enablePublicMethods&&j("enablePublicMethods option has been removed, public methods are now always available in the iFrame")}var e;return d(),C(),function(d,f){switch(e=[],c(d),typeof f){case"undefined":case"string":Array.prototype.forEach.call(document.querySelectorAll(f||"iframe"),b.bind(a,d));break;case"object":b(d,f);break;default:throw new TypeError("Unexpected data type ("+typeof f+")")}return e}}function E(a){a.fn?a.fn.iFrameResize||(a.fn.iFrameResize=function(a){function b(b,c){w(c,a)}return this.filter("iframe").each(b).end()}):i("","Unable to bind to jQuery, it is not fully loaded.")}if("undefined"!=typeof window){var F=0,G=!1,H=!1,I="message",J=I.length,K="[iFrameSizer]",L=K.length,M=null,N=window.requestAnimationFrame,O={max:1,scroll:1,bodyScroll:1,documentElementScroll:1},P={},Q=null,R="Host Page",S={autoResize:!0,bodyBackground:null,bodyMargin:null,bodyMarginV1:8,bodyPadding:null,checkOrigin:!0,inPageLinks:!1,enablePublicMethods:!0,heightCalculationMethod:"bodyOffset",id:"iFrameResizer",interval:32,log:!1,maxHeight:1/0,maxWidth:1/0,minHeight:0,minWidth:0,resizeFrom:"parent",scrolling:!1,sizeHeight:!0,sizeWidth:!1,warningTimeout:5e3,tolerance:0,widthCalculationMethod:"scroll",closedCallback:function(){},initCallback:function(){},messageCallback:function(){j("MessageCallback function not defined")},resizedCallback:function(){},scrollCallback:function(){return!0}};window.jQuery&&E(window.jQuery),"function"==typeof define&&define.amd?define([],D):"object"==typeof module&&"object"==typeof module.exports?module.exports=D():window.iFrameResize=window.iFrameResize||D()}}();
    //# sourceMappingURL=iframeResizer.map

    $(document).ready(function(){
        $('iframe').iFrameResize( [{log:true}] );
    });
    </script>
    <!-- END FOOTER -->

</body>
</html>

</html>