<template>
    <section id="image">
        <div class="inner">
            <div class="tit">
                <h2>강사진 프로필</h2>
                <p>드럼 스쿨의 실력 넘치는 강사님들을 소개합니다~</p>
            </div>
            <div class="cont">
                <article>
                    <figure><img src="../assets/img/photo01.svg" alt="프로필사진1"/></figure>
                    <figcaption>
                        <p>한승진 / 전문반</p>
                        <a href="/">자세히 보기</a>
                    </figcaption>
                </article>
                <article>
                    <figure><img src="../assets/img/photo02.svg" alt="프로필사진2"/></figure>
                    <figcaption>
                        <p>박상현 / 입시반</p>
                        <a href="/">자세히 보기</a>
                    </figcaption>
                </article>
                <article>
                    <figure><img src="../assets/img/photo03.svg" alt="프로필사진3"/></figure>
                    <figcaption>
                        <p>우지현 / 전문반</p>
                        <a href="/">자세히 보기</a>
                    </figcaption>
                </article>
            </div>
        </div>
    </section>
</template>

<style scoped>
    /* image */

#image {
    padding: 120px 0;
}
#image .cont {
    display: flex;
    justify-content: space-between;
}
#image .cont article {
    width: 30%;
    position: relative;
}
#image .cont article figcaption {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    padding: 20px 0;
    background: rgb(255 255 255 / 50%);
    text-align: center;
    background-blend-mode: color;
}
#image .cont article figcaption p {
    font-size: 24px;
    font-weight: 500;
    margin-bottom: 5px;
}
#image .cont article figcaption a {
    display: inline-block;
    height: 30px;
    line-height: 33px;
    padding: 0 15px;
    border-radius: 50px;
    color: #fff;
    background: #4857EC;
}
</style>