<template>
    <section id="imgText">
        <div class="inner">
            <div class="tit">
                <h2>연습실 구경하기</h2>
                <p>드럼 레슨이 이뤄지는 공간을 소개합니다.<br/>
                강의실 4개와 연습실 4개로 나뉘어져 직접 오셔서 예약제로 사용하실 수 있습니다.</p>
            </div>
            <ul>
                <li>
                    <figure><img src="../assets/img/room01.svg" alt="강의실A"/></figure>
                    <figcaption>
                        <h3>강의실 A룸<a href="/"></a></h3>
                        <p>Gretsch USA Custom 5pcs &amp; Yamaha Maple Custom snare / Zildjian A Custom set</p>
                    </figcaption>
                </li>
                <li>
                    <figure><img src="../assets/img/room02.svg" alt="강의실B"/></figure>
                    <figcaption>
                        <h3>강의실 B룸<a href="/"></a></h3>
                        <p>Gretsch New Classic 6pcs / Zildjian A Custom set</p>
                    </figcaption>
                </li>
                <li>
                    <figure><img src="../assets/img/room03.svg" alt="강의실C"/></figure>
                    <figcaption>
                        <h3>강의실 C룸<a href="/"></a></h3>
                        <p>DrumCraft &amp; Basileia Gemstone Cymbals</p>
                    </figcaption>
                </li>
                <li>
                    <figure><img src="../assets/img/room04.svg" alt="강의실D"/></figure>
                    <figcaption>
                        <h3>강의실 D룸<a href="/"></a></h3>
                        <p>Tama Starclassic Performer / Paiste Signature Precision Universal Set</p>
                    </figcaption>
                </li>
                <li>
                    <figure><img src="../assets/img/room05.svg" alt="연습실1"/></figure>
                    <figcaption>
                        <h3>연습실 1룸<a href="/"></a></h3>
                        <p>Mapex Saturn 4 MH Exotic 5pcs / Paiste Signature Precision Universal Set</p>
                    </figcaption>
                </li>
                <li>
                    <figure><img src="../assets/img/room06.svg" alt="연습실2"/></figure>
                    <figcaption>
                        <h3>연습실 2룸<a href="/"></a></h3>
                        <p>Gretsch Renown57 5pcs / Sabian AAX Set</p>
                    </figcaption>
                </li>
                <li>
                    <figure><img src="../assets/img/room07.svg" alt="연습실3"/></figure>
                    <figcaption>
                        <h3>연습실 3룸<a href="/"></a></h3>
                        <p>Gretsch Catalina Maple 5pcs / Sabian AAX Set</p>
                    </figcaption>
                </li>
                <li>
                    <figure><img src="../assets/img/room08.svg" alt="연습실4"/></figure>
                    <figcaption>
                        <h3>연습실 4룸<a href="/"></a></h3>
                        <p>Mapex Saturn 4 MH Exotic 6pcs / Mapex Black Panther Snare / Zildjian A Custom set</p>
                    </figcaption>
                </li>
            </ul>
        </div>
    </section>
</template>

<style scoped>
    /* imgText */
    #imgText {
        padding: 120px 0 70px 0;
        background: #F6F8FD;
    }
    #imgText ul {
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
    }
    #imgText ul li {
        width: 23.5%;
        margin-bottom: 50px;
    }
    #imgText ul li figcaption {
        padding: 20px 0;
    }
    #imgText ul li figcaption h3 {
        font-weight: 500;
        font-size: 28px;
        margin-bottom: 10px;
        display: flex;
        justify-content: space-between;
    }
    #imgText ul li figcaption h3 a {
        display: inline-block;
        width: 25px;
        height: 25px;
        background: url(../assets/img/more.svg) no-repeat;
    }
    #imgText ul li figcaption p {
        font-size: 18px;
        line-height: 1.3;
        display: -webkit-box;
        word-wrap: break-word;
        -webkit-line-clamp: 3;
        -webkit-box-orient: vertical;
        overflow: hidden;
        text-overflow: ellipsis;
    }
</style>