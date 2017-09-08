<template>
    <div style="height: 100%;">
        <header id="home" class="welcome-area">
            <div class="header-top-area">
                <!--div class="container black-bg">
                    <div class="row">
                        <div class="col-sm-3">
                            <div class="logo">
                                <a href="index.html">DL</a>
                            </div>
                        </div>
                        <div class="col-sm-9">
                            <!--div class="mainmenu">
                                <div class="navbar navbar-nobg">
                                    <div class="navbar-header">
                                        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                                            <span class="sr-only">Toggle navigation</span>
                                            <span class="icon-bar"></span>
                                            <span class="icon-bar"></span>
                                            <span class="icon-bar"></span>
                                        </button>
                                    </div>
                                    <div class="navbar-collapse collapse">
                                        <ul class="nav navbar-nav navbar-right">
                                            <li class="active"><a class="smoth-scroll" href="#home">Home <div class="ripple-wrapper"></div></a>
                                            </li>
                                            <li><a class="smoth-scroll" href="#about">About</a>
                                            </li>
                                            <li><a class="smoth-scroll" href="#service">service</a>
                                            </li>
                                            <li><a class="smoth-scroll" href="#work">Work</a>
                                            </li>
                                            <li><a class="smoth-scroll" href="#testimonial">testimonial</a>
                                            </li>
                                            <li><a class="smoth-scroll" href="#contact">Contact</a>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div-->
            </div>
            <div class="welcome-image-area" data-stellar-background-ratio="0.6" style="background-position: 0% 0%;">
                <!--div id="particles-js"></div-->
                <vue-particles
                    color="#ddd"
                    :particlesNumber="80"
                    :particleOpacity="0.7"
                    shapeType="circle"
                    :particleSize="4"
                    linesColor="#dedede"
                    :linesWidth="1"
                    :lineLinked="true"
                    :lineOpacity="0.4"
                    :linesDistance="150"
                    :moveSpeed="3"
                    :hoverEffect="true"
                    hoverMode="grab"
                    :clickEffect="true"
                    clickMode="push"
                >
                </vue-particles>
                <div class="display-table">
                    <div class="display-table-cell">
                        <div class="container">
                            <div class="row">
                                <div class="col-md-12">
                                    <div class="header-text">
                                        <h1>{{ msg }}</h1>
                                        <div class="social-links header-links">
                                            <ul>
                                                <li><a href="mailto:lagrezd@gmail.com" target="_blank" title="Me contacter par mail"><icon name="envelope" scale="2"></icon></a></li>
                                                <li><a href="https://www.linkedin.com/in/damien-lagreze/" title="Voir mon profil LinkedIn"><icon name="linkedin" scale="2" target="_blank"></icon></a></li>
                                                <li><a href="https://github.com/lagrezd" target="_blank" title="Voir mon compte GitHub"><icon name="github" scale="2"></icon></a></li>
                                            </ul>
                                        </div>
                                        <h2>Développeur Web</h2>
                                        Basé sur Bordeaux, je suis disponible pour de nouveaux projets en freelance.
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </header>
        <footer class="footer-area">
            <div class="container">
                <div class="row">
                    <div class="col-sm-12 text-center wow fadeInUp" data-wow-delay="0.2s">
                        <p>&copy; 2017 Damien Lagreze | Tous droits réservés.</p>
                    </div>
                </div>
            </div>
        </footer>
    </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Damien Lagreze'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .welcome-image-area {
        position: relative;
        height: 100%;
        background: url(/static/img/bryan-goff-360297.jpg);
        background-size: cover;
        z-index: 1;
    }
    /*
    * ----------------------------------------------------------------------------------------
    Author       : Onepageboss
    Template Name: Expert - Creative Personal Portfolio Template
    Version      : 1.0
    * ----------------------------------------------------------------------------------------
    */


    /*
    * ----------------------------------------------------------------------------------------
    * 01.GLOBAL CSS STYLE
    * 02.PRELOADER & BOUNCE CCS STYLE
    * 03.HOMEPAGE CSS STYLE
        -LOGO CSS
        -MENU CSS
        -VIDEO BACKGROUND CSS STYLE
    * 04.QUOTES CSS STYLE
    * 05.ABOUT CSS STYLE
    * 06.SERVICE CSS STYLE
    * 07.WORK CSS STYLE
    * 08.TESTIMONIAL CSS STYLE
    * 09.CONTACT CSS STYLE
    * 10.FOOTER CSS STYLE
    * ----------------------------------------------------------------------------------------
    */


    /*
    * ----------------------------------------------------------------------------------------
    * 01.GLOBAL STYLE
    * ----------------------------------------------------------------------------------------
    */

    body {
        font-size: 14px;
        font-weight: 300;
        line-height: 24px;
        height: 100%;
        font-family: 'Poppins', sans-serif;
        /* color: #232323; */
        color: #fff;
    }

    html,
    body {
        height: 100%
    }

    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
        font-family: 'Raleway', sans-serif;
    }

    a {
        text-decoration: none;
        -webkit-transition: all 0.4s;
        -webkit-transition: all 0.2s;
        transition: all 0.2s;
        color: #000;
    }

    img {
        width: 100%;
    }

    a:hover {
        color: #fff;
        text-decoration: none;
    }

    a:focus {
        outline: none;
        text-decoration: none;
    }

    p {
        line-height: 32px;
    }

    ul,
    li {
        margin: 0;
        padding: 0;
        list-style: none;
    }

    fieldset {
        border: 0 none;
        margin: 0 auto;
        padding: 0;
    }

    .no-padding {
        padding: 0
    }

    .section-padding {
        padding: 70px 0px;
    }

    .section-title {
        text-align: center;
        margin-bottom: 60px;
    }

    .section-title h2 {
        margin-top: 0;
        font-weight: 700;
        text-transform: capitalize;
        font-size: 40px;
    }

    .white-title h2 {
        color: #fff;
    }

    .section-title p {
        font-weight: 300;
    }

    .dark-bg {
        background: #262B2D;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 02.PRELOADER & BOUNCE CCS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .preloader {
        background: #000;
        bottom: 0;
        left: 0;
        position: fixed;
        right: 0;
        top: 0;
        z-index: 99999;
    }

    .status-mes {
        width: 45px;
        height: 45px;
        position: absolute;
        top: 50%;
        left: 50%;
        margin: -22px 0 0 -22px;
        font-size: 10px;
        text-indent: -12345px;
        border-top: 8px solid #222;
        border-right: 8px solid #222;
        border-bottom: 8px solid #222;
        border-left: 8px solid #fff;
        border-radius: 50%;
        -webkit-animation: spinner 1000ms infinite linear;
        animation: spinner 1000ms infinite linear;
        z-index: 10000;
    }

    @-webkit-keyframes spinner {
        0% {
            -webkit-transform: rotate(0deg);
            transform: rotate(0deg);
        }
        100% {
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
        }
    }

    @keyframes spinner {
        0% {
            -webkit-transform: rotate(0deg);
            transform: rotate(0deg);
        }
        100% {
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
        }
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 03.HOMEPAGE CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .welcome-area {
        height: 100%;
    }

    #particles-js {
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
    }

    .welcome-image-area {
        position: relative;
        height: 100%;
        /*background: url(../images/bg/bg.jpg);*/
        background-size: cover;
        z-index: 1;
    }

    .welcome-image-area:after {
        position: absolute;
        background: rgba(0, 0, 0, .2);
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        content: "";
        z-index: -1;
    }

    .particle-bg {
        position: relative;
        height: 100%;
        /*background: url(../images/bg/bg2.jpg);*/
        background-size: cover;
        z-index: 1;
    }

    .particle-bg:after {
        position: absolute;
        background: rgba(0, 0, 0, .6);
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        content: "";
        z-index: -1;
    }

    .display-table {
        display: table;
        width: 100%;
        height: 100%;
    }

    .display-table-cell {
        display: table-cell;
        vertical-align: middle;
    }

    .header-text {
        padding-top: 300px;
    }

    .header-text h1 {
        color: #fafafa;
        font-size: 70px;
        font-weight: 600;
        text-transform: capitalize;
    }

    .header-text h2 {
        color: #fafafa;
        font-size: 20px;
        font-weight: 400;
    }

    .black-bg {
        background: rgba(0, 0, 0, .6);
        margin-top: 30px;
    }

    .menu-bg .black-bg {
        background: #000;
        margin-top: 30px;
    }

    .header-top-area {
        position: fixed;
        left: 0;
        top: 0;
        width: 100%;
        z-index: 999;
        -webkit-transition: all 0.4s ease-out;
        transition: all 0.4s ease-out;
    }

    .logo {
        padding-top: 28px;
        -webkit-transition: all 0.3s ease-out;
        transition: all 0.3s ease-out;
    }

    .logo a {
        display: block;
        color: #fff;
        text-transform: capitalize;
        font-weight: 700;
        font-size: 40px;
    }

    .mainmenu .navbar-nav li a {
        color: #fff;
        font-size: 10px;
        padding: 30px 15px;
        -webkit-transition: .3s;
        transition: .3s;
        font-weight: 400;
        font-family: 'Montserrat', sans-serif;
        text-transform: uppercase;
    }

    .mainmenu .navbar-nav li a:hover {
        background: none;
        color: #fff;
        -webkit-transition: all 0.3s ease-out;
        transition: all 0.3s ease-out;
    }

    .nav li a:focus,
    .nav li a:hover {
        background: none;
        color: #fff;
        -webkit-transition: all 0.3s ease-out;
        transition: all 0.3s ease-out;
    }

    .navbar {
        margin: 0;
    }

    .menu-bg .logo {
        padding-top: 18px;
        -webkit-transition: all 0.3s ease-out;
        transition: all 0.3s ease-out;
    }

    .menu-bg .mainmenu .navbar-nav li a {
        color: #fff;
        padding: 20px 15px;
        -webkit-transition: .3s;
        transition: .3s;
    }

    .menu-bg .mainmenu .navbar-nav li a:hover {
        color: #fff;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * VIDEO BACKGROUND CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .welcome-video-area {
        position: relative;
        height: 100%;
        background-size: cover;
        z-index: 1;
        background-position: center center;
    }

    .welcome-video-area:after {
        position: absolute;
        background: rgba(0, 0, 0, .5);
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        content: "";
        z-index: -1;
    }

    .display-table {
        display: table;
        width: 100%;
        height: 100%;
    }

    .display-table-cell {
        display: table-cell;
        vertical-align: middle;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 04.QUOTES CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .quotes-area {
        background: #f7f7f7;
        padding: 100px 0px;
    }

    .quotes-text {
        padding: 0px 100px;
    }

    .quotes-text h2 {
        font-size: 24px;
        line-height: 40px;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 05.ABOUT CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .about-me-area .col-md-6 {
        padding: 0;
    }

    .about-image {}

    .about-text {
        padding: 50px;
    }

    .about-text h2 {
        font-size: 40px;
        text-transform: capitalize;
        margin-top: 0;
        margin-bottom: 60px;
        color: #fff;
        font-weight: 700;
        position: relative;
    }

    .about-text h2:before {
        position: absolute;
        left: 50%;
        top: 120px;
        height: 1px;
        width: 100px;
        background: #fff;
        content: "";
        margin-left: -50px;
    }

    .about-text p {
        font-weight: 300;
        margin-bottom: 30px;
        color: #fff;
    }

    .about-text a {
        display: inline-block;
        background: #fff;
        padding: 10px 20px;
        border: 1px solid #fff;
        text-transform: uppercase;
    }

    .about-text a:hover {
        -webkit-transition: .3s;
        transition: .3s;
        background: transparent;
        border: 1px solid #fff;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 06.SERVICE CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .service-area {
        /*background: url(../images/bg/service-bg.jpg);*/
        padding: 70px 0px;
        background-size: cover;
        background-attachment: fixed;
        position: relative;
        z-index: 1;
    }

    .service-area:after {
        position: absolute;
        background: rgba(0, 0, 0, .7);
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        content: "";
        z-index: -1;
    }

    .single-service {
        text-align: center;
        padding: 10px;
    }

    .single-service i {
        font-size: 40px;
        margin-bottom: 10px;
        -webkit-transition: .3s;
        transition: .3s;
        background: #F5F5F5;
        height: 80px;
        width: 80px;
        border-radius: 50%;
        text-align: center;
        color: #1C1C1C;
        line-height: 80px;
    }

    .single-service h2 {
        font-size: 16px;
        text-transform: capitalize;
        margin: 20px 0px;
        -webkit-transition: .3s;
        transition: .3s;
        color: #fff;
        font-weight: 700;
    }

    .single-service p {
        color: #fff;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 07.WORK CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .work {
        background: #F7F7F7;
    }

    .work-inner .mix {
        display: none;
    }

    ul.work {
        padding: 0;
        list-style: none;
        text-align: center;
        margin-bottom: 30px;
    }

    ul.work li {
        display: inline-block;
        padding: 5px 10px;
        margin: 0 10px;
        text-transform: capitalize;
        font-size: 14px;
        font-weight: 300;
        color: #333;
        border: 1px solid transparent;
        cursor: pointer;
        border-radius: 30px;
    }

    ul.work li:hover {
        border: 1px solid #333;
        -webkit-transition: .3s;
        transition: .3s;
    }

    ul.work li.active {
        border: 1px solid #333;
    }

    .work .item {
        padding: 0;
        margin: 0;
    }

    .work .col-md-6 {
        padding: 0;
        margin: 0;
    }

    .work figure.effect-ruby img {
        height: auto;
        width: 100%;
    }

    .work .grid figure {
        position: relative;
        float: left;
        overflow: hidden;
        width: 100%;
        height: auto;
        text-align: center;
        cursor: pointer;
        padding: 0;
        margin: 0;
    }

    .work .grid figure:hover {
        background: #000;
    }

    .work figure.effect-ruby h2 {
        margin-top: 26%;
        opacity: 0;
        -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=0)";
        font-size: 40px;
        text-transform: capitalize;
        font-weight: 600;
        -webkit-transition: .3s;
        transition: .3s;
        display: inline-block;
        color: #fff;
    }

    .work figure.effect-ruby p {
        font-size: 14px;
        text-transform: capitalize;
        border: none;
        padding: 0;
        margin: 5px 0px;
    }

    .work figure.effect-ruby p strong {
        font-size: 16px;
        text-transform: uppercase;
        margin-right: 5px;
    }

    .work .item:hover figure.effect-ruby h2 {
        opacity: 1;
        -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=100)";
        -webkit-transition: .3s;
        transition: .3s;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 08.TESTIMONIAL CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .testimonial-area {
        background: #262B2D;
    }

    .testimonial-list {}

    .single-testimonial h2 {
        font-size: 12px;
        text-transform: uppercase;
        -webkit-transition: .3s;
        transition: .3s;
        color: #fafafa;
        letter-spacing: 2px;
        font-weight: 700;
    }

    .single-testimonial h3 {
        font-size: 12px;
        text-transform: capitalize;
        font-weight: 300;
        margin-top: 0;
        color: #fff;
    }

    .single-testimonial p {
        font-size: 20px;
        line-height: 38x;
        color: #fafafa;
    }

    .single-testimonial img {
        width: 50px;
        margin: 0 auto;
        border-radius: 50%;
        border: 2px solid rgba(255, 255, 255, 0.1);
        margin-top: 20px;
    }

    .testimonial-area .owl-theme .owl-controls .owl-page span {
        display: block;
        width: 5px;
        height: 5px;
        margin: 5px 7px;
        border-radius: 20px;
        background: #fff;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 09.CONTACT CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .contact-me-area {}

    .form-control {
        display: block;
        border: 0px;
        width: 100%;
        height: 45px;
        padding: 5px 10px;
        font-size: 16px;
        line-height: 1.42857143;
        color: #333;
        background-color: #F7F7F7;
        background-image: none;
        border-radius: 0px;
        box-shadow: none;
        margin-bottom: 25px;
    }

    .form-control:focus {
        border-color: #000;
        outline: 0;
        box-shadow: none;
    }

    .contact-form button.btn {
        display: inline-block;
        color: #fff;
        background: none;
        padding: 15px 25px;
        border: 1px solid #333;
        font-size: 14px;
        border-radius: 0px;
        font-weight: 300;
        -webkit-transition: .3s;
        transition: .3s;
        background: #232323;
        text-transform: capitalize;
        border-radius: 30px;
    }

    .contact-form button.btn:hover {
        background: transparent;
        border: 1px solid #000;
        color: #000;
        -webkit-transition: all 0.4s;
        -webkit-transition: all 0.2s;
        transition: all 0.2s;
    }

    .input-success,
    .input-error {
        margin-bottom: 0;
        margin-top: 10px;
        border-radius: 4px;
        display: none;
    }

    .input-success {
        border: 1px solid #01B500;
    }

    .input-error {
        border: 1px solid #ff0000;
    }


    /*
    * ----------------------------------------------------------------------------------------
    * 10.FOOTER CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .footer-area {
        background: #000000;
        padding: 120px 0px;
    }

    .social-links ul {
        padding: 0;
        margin: 0;
    }

    .social-links ul li {
        display: inline-block;
        margin-bottom: 10px;
    }

    .social-links ul li a {
        font-size: 18px;
        color: #fff;
        margin: 0px 10px;
        display: block;
    }

    .header-links ul li a {
        color: #fafafa;
    }

    .footer-area p {
        margin-bottom: 0;
        font-size: 14px;
        color: #fff;
    }



    /*
    * ----------------------------------------------------------------------------------------
    * PREVIEW CSS STYLE
    * ----------------------------------------------------------------------------------------
    */

    .preview-body {
        background: #fafafa;
    }

    .preview-single-image img {
        width: 100%;
    }

    .preview-single-image {
        -webkit-transition: 1s;
        transition: 1s;
        box-shadow: 1px 2px 2px 0px rgba(0, 0, 0, 0.05);
        margin-bottom: 30px;
    }

    .preview-single-image:hover {
        -webkit-transition: 1s;
        transition: 1s;
        box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
    }

    .preview-single-image h2 {
        font-size: 20px;
        text-align: center;
        color: #000;
        background: #fff;
        margin: 0;
        padding: 30px 20px;
    }

    .preview-header-top-area {
        padding: 50px 0px;
    }

    .preview-header-top-area h2 {
        font-size: 80px;
        color: #232323;
        text-transform: capitalize;
        font-weight: 900;
    }

    .preview-header-top-area p {
        color: #333;
        font-size: 30px;
        font-weight: 300;
    }

    .main h2 {
        color: #000;
    }

    .main {
        margin-bottom: 120px;
    }
</style>
