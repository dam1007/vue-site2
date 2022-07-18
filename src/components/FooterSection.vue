<template>
    <footer id="footer">
        <div class="inner">
            <div class="footer-top">
                <div class="footer-left">
                    <h3 class="name">Dami</h3>
                    <p>
                    안녕하세요!<br/>
                    더 다양한 정보 확인<br/>
                    drumclass@naver.com
                    </p>
                    <ul class="sns">
                        <li><a href="/"></a></li>
                        <li><a href="/"></a></li>
                        <li><a href="/"></a></li>
                        <li><a href="/"></a></li>
                        <li><a href="/"></a></li>
                    </ul>
                </div>
                <div class="footer-right">
                    <ul class="menu">
                    <h3>사이트</h3>
                        <li><a href="/">웹표준 사이트</a></li>
                        <li><a href="/">반응형 사이트</a></li>
                        <li><a href="/">패럴랙스 사이트</a></li>
                        <li><a href="/">포트폴리오 사이트</a></li>
                    </ul>
                    <ul class="menu">
                        <h3>유형</h3>
                        <li><a href="/">이미지 유형</a></li>
                        <li><a href="/">카드 유형</a></li>
                        <li><a href="/">이미지/텍스트 유형</a></li>
                        <li><a href="/">배너 유형</a></li>
                        <li><a href="/">텍스트 유형</a></li>
                        <li><a href="/">푸터 유형</a></li>
                    </ul>
                    <ul class="menu">
                        <h3>스크립트</h3>
                        <li><a href="/">검색 이펙트</a></li>
                        <li><a href="/">퀴즈 이펙트</a></li>
                        <li><a href="/">마우스 이펙트</a></li>
                        <li><a href="/">슬라이드 이펙트</a></li>
                        <li><a href="/">패럴랙스 이펙트</a></li>
                        <li><a href="/">게임 이펙트</a></li>
                    </ul>
                    <ul class="menu">
                        <h3>레퍼런스</h3>
                        <li><a href="/">CSS</a></li>
                        <li><a href="/">FONTS</a></li>
                        <li><a href="/">BLOG</a></li>
                        <li><a href="/">REFERENCE</a></li>
                        <li><a href="/">TUTORIAL</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>Copyright 2022. All Rights Reserved. - Designed by Dami</p>
            </div>
        </div>
    </footer>
</template>

<style>
    /* footer */
    #footer {
        background: #fff;
        padding: 120px 0;
        font-family: 'NexonLv1Gothic';
    }
    #footer .footer-top {
        padding-bottom: 67px;
        border-bottom: 1px solid #ddd;
        display: flex;
    }
    #footer .footer-left {
        width: 33.33%;
    }
    #footer .footer-left .name {
        font-size: 18px;
        font-weight: 700;
        margin-bottom: 20px;
    }
    #footer .footer-left p {
        font-size: 14px;
        font-weight: 400;
        line-height: 1.595;
        margin-bottom: 25px;
    }
    #footer .footer-left .sns li {
        display: inline-block;
        margin-right: 3px;
    }
    #footer .footer-left .sns li:last-child {
        margin-right: 0;
    }

    #footer .footer-left .sns li a {
        display: inline-block;
        width: 45px;
        height: 45px;
        border-radius: 100%;
        background: #f5f5f5 url(../assets/img/facebook.svg) no-repeat 50% 50%;
    }
    #footer .footer-left .sns li:nth-child(2) a {
        background-image: url(../assets/img/instagram.svg);
    }
    #footer .footer-left .sns li:nth-child(3) a {
        background-image: url(../assets/img/youtube.svg);
    }
    #footer .footer-left .sns li:nth-child(4) a {
        background-image: url(../assets/img/git.svg);
    }
    #footer .footer-left .sns li:nth-child(5) a {
        background-image: url(../assets/img/link.svg);
    }

    #footer .footer-right {
        width: 66.66%;
        display: flex;
    }
    #footer .footer-right .menu {
        width: 25%;
    }
    #footer .footer-right .menu h3 {
        margin-bottom: 13px;
    } 
    #footer .footer-right .menu li a {
        display: inline-block;
        font-size: 14px;
        padding: 5px 0;
    }

    #footer .footer-bottom {
        padding-top: 33px;
    }
    #footer .footer-bottom p {
        font-size: 14px;
        font-weight: 300;
        text-align: center;
    }
</style>