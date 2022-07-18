<template>
    <section id="contents">
        <div class="inner">
            <div class="left">
                <em>CLASS</em>
                <h2>드럼스쿨<br/>
                수강생 모집</h2>
                <p>취미반/입시반/전문반<br/>
                전 분야 모집!<br/>
                이런 분들이 들으면 좋아요~
                </p>
                <a class="consult" href="/">상담받기</a>
            </div>
            <div class="right">
                <ul>
                <li>
                    <span class="icon"></span>
                    <h3>취미반</h3>
                    <p>멋있는 취미를 가지고 싶은 분들께 추천해요. 기본기부터 시작하기 때문에 드럼을 처음 치는 초보자 분들이 들으시면 좋습니다.</p>
                </li>
                <li>
                    <span class="icon"></span>
                    <h3>입시반</h3>
                    <p>드럼을 전공으로 하고 싶은 분들께 추천해요. 예중, 예고, 예대 입시를 다니고 싶으신 분들이 들으시면 좋습니다.</p>
                </li>
                <li>
                    <span class="icon"></span>
                    <h3>전문반(프로)</h3>
                    <p>프로를 지망하시는 분들께 추천해요. 취미반보다 심층적이며 프로에 준하는 내용을 배울 수 있습니다. 취미반보다 조금 더 깊게 배우고 싶으신 분들도 환영합니다!</p>
                </li>
                <li>
                    <span class="icon"></span>
                    <h3>전문반(오디션)</h3>
                    <p>오디션을 보시는 분들께 추천해요. 오디션은 입시반, 전문반보다 특수한 케이스로 곡 선정부터 시작해 오디션에 대한 정보들을 알려드립니다.</p>
                </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<style scoped>
    /* contents */
    #contents {
        background: #F6F8FD;
        padding: 120px 0 65px 0;
    }
    #contents .inner {
        display: flex;
    }
    #contents .left {
        width: 33.33%;
    }
    #contents .left em {
        display: inline-block;
        font-size: 14px;
        color: #fff;
        background: #FF3344;
        border-radius: 50px;
        padding: 3px 25px;
        margin-bottom: 13px;
    }
    #contents .left h2 {
        font-size: 50px;
        font-weight: bold;
        margin-bottom: 20px;
    }
    #contents .left p {
        font-size: 18px;
        line-height: 1.5;
        margin-bottom: 70px;
    }
    #contents .left .consult {
        display: inline-block;
        background: #4857EC;
        color: #fff;
        font-size: 18px;
        padding: 10px 50px;
    }

    #contents .right {
        width: 66.66%;
    }
    #contents .right ul {
        display: flex;
        flex-wrap: wrap;
    }
    #contents .right ul li {
        width: 50%;
        margin-bottom: 55px;
        padding-right: 40px;
        box-sizing: border-box;
    }
    #contents .right ul li .icon {
        display: inline-block;
        width: 60px;
        height: 60px;
        background: url(../assets/img/icon01.png) no-repeat;
        margin-bottom: 10px;
    }
    #contents .right ul li:nth-child(2) .icon {
        background-image: url(../assets/img/icon02.png);
    }
    #contents .right ul li:nth-child(3) .icon {
        background-image: url(../assets/img/icon03.png);
    }
    #contents .right ul li:nth-child(4) .icon {
        background-image: url(../assets/img/icon04.png);
    }

    #contents .right ul li h3 {
        font-size: 24px;
        font-weight: 500;
        margin-bottom: 20px;
    }
    #contents .right ul li p {
        font-size: 18px;
        font-weight: 100;
        line-height: 1.6;
    }
</style>