<template>
    <header id="header">
        <h1 class="logo">Drum School</h1>
        <nav>
            <ul class="gnb">
            <li><a href="/">학원 소개</a></li>
            <li><a href="/">클래스 소개</a></li>
            <li><a href="/">강사진 소개</a></li>
            <li><a href="/">입시/오디션 정보</a></li>
            <li><a href="/">오시는 길</a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
    /* header */
    #header {
        background: #F6F8FD;
        text-align: center;
    }
    #header .logo {
        padding-top: 20px;
    }
    #header nav {
        max-width: 1160px;
        margin: 0 auto;
    }
    #header .gnb {
        display: flex;
    }
    #header .gnb li {
        width: 20%;
    }
    #header .gnb li a {
        display: inline-block;
        line-height: 56px;
    }
    #header .gnb li a:hover {
        text-decoration: underline;
    }
</style>