<template>
    <section id="review">
        <div class="inner">
            <div class="tit">
                <h2>클래스 후기</h2>
                <p>수강생들의 후기를 소개합니다. 믿고 맡길 수 있는 드럼 클래스 입니다.</p>
            </div>
            <ul>
                <li>
                <p class="review">불과 3달전만해도 여러 원인들로 인해 자존감이 밑바닥이였던 저에게 이 드럼 클래스의 레슨은 너무 소중한 시간이었어요. 
                    매일 마음속으로 울고싶다를 외쳤던 저였는데 이제는 조금이나마 이겨 낼 수 있을 것 같네요. 
                    다음에 선생님 만났을 때는 많이 발전해있는 제가 되었으면 좋겠네요...
                </p>
                <div class="user">
                    <div class="user-left">
                    <img src="../assets/img/user01.png" alt="사용자01"/>
                    <span class="profile"></span>
                    </div>
                    <div class="user-right">
                    <p><strong class="name">이주형</strong>
                        <em class="info">전문반(오디션)</em>
                    </p>
                    <div class="star">
                        <img src="../assets/img/star.png" alt="평점"/>
                    </div>
                    </div>
                </div>
                <div class="more">
                    <a href="/">자세히 보기</a>
                </div>
                </li>
                <li>
                <p class="review">뒤늦게 드러머의 꿈을 꾸고 고2 때 부랴부랴 입시를 시작했습니다.
                    늦게 시작했다는 초조함 때문에 불안이 더욱 커져갔는데 쌤께서 멘탈 관리도 잘 해주시고 잘 지도해주신 덕분에 원하는 학교에 합격하게 되었어요!
                    ㅇㅇ쌤 정말 감사드립니다ㅠㅠㅠ
                </p>
                <div class="user">
                    <div class="user-left">
                    <img src="../assets/img/user02.png" alt="사용자02"/>
                    <span class="profile"></span>
                    </div>
                    <div class="user-right">
                    <p><strong class="name">김태연</strong>
                        <em class="info">입시반</em>
                    </p>
                    <div class="star">
                        <img src="../assets/img/star.png" alt="평점"/>
                    </div>
                    </div>
                </div>
                <div class="more">
                    <a href="/">자세히 보기</a>
                </div>
                </li>
                <li>
                <p class="review">취미반이어서 반신반의 했는데 강사님이 친절하시고 제 속도에 맞춰 하나하나 알려주셔서 좋았어요.
                    물어보시는 것도 잘 알려주시고 취미반이니만큼 여유롭게 음악을 즐기는 것에 초점을 맞춰 주셨습니다.
                    보다 전문적인 내용을 배우고 싶으시다면 취미반을 하시다 심화반으로 넘어가시는 것을 추천드립니다! ㅇㅇ쌤 최고bbb
                </p>
                <div class="user">
                    <div class="user-left">
                    <img src="../assets/img/user03.png" alt="사용자03"/>
                    <span class="profile"></span>
                    </div>
                    <div class="user-right">
                    <p><strong class="name">박재형</strong>
                        <em class="info">취미반</em>
                    </p>
                    <div class="star">
                        <img src="../assets/img/star.png" alt="평점"/>
                    </div>
                    </div>
                </div>
                <div class="more">
                    <a href="/">자세히 보기</a>
                </div>
                </li>
            </ul>
        </div>
    </section>
</template>

<style>
    /* review */
    #review {
        padding: 120px 0;
        background: #F6F8FD;
    }
    #review ul {
        display: flex;
        justify-content: space-between;
    }
    #review ul li {
        width: 32%;
        background: #fff;
        border-radius: 10px;
        padding: 30px;
        box-sizing: border-box;
    }

    #review ul li .review {
        font-family: 'NexonLv1Gothic';
        font-size: 18px;
        font-weight: 500;
        line-height: 1.5;
        display: -webkit-box;
        word-wrap: break-word;
        -webkit-line-clamp: 6;
        -webkit-box-orient: vertical;
        text-overflow: ellipsis;
        overflow: hidden;
        margin-bottom: 20px;
    }
    #review ul li .user {
        padding: 20px 0;
        border-top: 1px solid #ddd;
        border-bottom: 1px solid #ddd;
        display: flex;
        
    }
    #review ul li .user .user-left {
        width: 15%;
    }
    #review ul li .user .user-right {
        width: 75%;
        padding-left: 15px;
    }
    #review ul li .user .user-right .name {
        font-size: 26px;
        font-weight: 500;
    }
    #review ul li .user .user-right .star {
        height: 15px;
        margin-top: 7px;
    }
    #review ul li .user .user-right .star img {
        width: auto;
        height: 100%;
    }
    #review ul li .more {
        text-align: center;
        padding-top: 20px;
    }
    #review ul li .more a {
        display: inline-block;
        height: 30px;
        line-height: 33px;
        padding: 0 15px;
        border-radius: 50px;
        font-size: 14px;
        font-weight: 500;
        color: #fff;
        background: #4857EC;
    }
</style>