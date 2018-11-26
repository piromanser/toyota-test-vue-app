<template>
    <div class="container">
        <div class="price-aside">
            <div class="name-block">
                <div class="name">
                    <div>                         
                        <p>Fortuner</p>
                        <p>Ты настоящий</p>
                    </div>
                </div>
            </div>
            <div class="price-block">
                <div class="price-block-itm">
                    <p class="lil-latters">Кредит в день от<br><span class="capital-latters">304 ₽*</span></p>
                </div>
                <div class="price-block-itm">
                    <p class="lil-latters">Выгода до<br><span class="capital-latters">365 000 ₽*</span></p>
                </div>
                <div class="price-block-itm">
                    <p class="lil-latters">Скидка по trade-in до<br><span class="capital-latters">50 000 ₽*</span></p>
                </div>
                <div class="price-block-itm">
                    <p class="lil-latters">В подарок<br><span class="capital-latters">3 ТО</span></p>
                </div>
                <div class="price-block-itm">
                    <p class="lil-latters">В подарок<br><span class="capital-latters">зимние шины</span></p>
                </div>
            </div>
            <div class="test-drive-block">
                <div class="test-drive">
                    <img src="../assets/test-drive-pic.png" alt="">
                    <a href="#">Записаться на Тест-драйв</a>
                </div>
                <div class="offer-block">    
                    <div class="offer-button">
                        <a href="#">Получить предложение</a>
                    </div>
                    <p>Нашли дешевле?</p>
                </div>
            </div>
        </div>
        <div class="pic-block">
            <img class="pic1" src="../assets/pic-block-bg.png" alt="">
            <img class="pic2" src="../assets/pic-block-img.png" alt="">
            <img class="price-pic" src="../assets/pic-block-price.png" alt="">
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .container {
        display: flex;
    }

    .name-block {
        width: 237px;
        height: 122px;
        background-image: url('../assets/name-bg.png');
        background-repeat: no-repeat;
        background-position: center center;
    }

    .name {
        color: #333333;      
        position: relative;
    }

    .name p:nth-child(1) {
        font-size: 32px;
        margin: 0;
        margin-bottom: 8px;;
        color: #ffffff;
        letter-spacing: 0.16px;

    }

    .name p:nth-child(2) {
        font-size: 24px; 
        margin: 0;
        letter-spacing: 0.12px;
    }

    .name div {
        position: relative;
        top: 41px;
        left: 43px;
    }

    .lil-latters {
        font-size: 13px;
        letter-spacing: 0.01px;
    }

    .capital-latters {
        font-size: 16px;
        font-weight: 700px;
        text-transform: uppercase;
    }

    .price-aside {
        flex: 1;
    }

    .pic-block {
        flex: 2;
    }

    .price-block {
        display: flex;
        flex-wrap: wrap;
    }

    .price-block-itm {
        margin:0 15px 0 0;
        width: 135px;
    }

    .pic-block {
        position: relative; 
    }

    .pic-block img:not(.price-pic) {
        position: absolute;
        width: 70%;
    }

    .pic1 {
        top: 0;
        left: auto;
        right: 0;
        bottom: auto;
    }

    .pic2 {
        top: auto;
        left: 0;
        right: auto;
        bottom: 0;
    }

    .price-pic {
        margin-top: 15px;
        margin-left: 120px;
    }

    .test-drive {
        display: flex;
        align-items: center;
    }

    .test-drive img {
        margin-right: 5px;
    }    

    .test-drive a {
        letter-spacing: 0.08px;
        color: #e50000;
    }

    .offer-block {
        display: inline-block;
    }

    .offer-block p {
        border-bottom: dotted 2px #e50000;
        display: inline-block;
        text-align: right;
    }
    .offer-button {
        background-color: #e50000;
        display: inline-block;
        padding: 17px 36px 17px 36px;
        margin-top: 17px;
        border-radius: 25px;
    }

    .offer-button a {
        color: #ffffff;
        text-decoration: none;
    }
</style>
