<template>
    <div class="container">
        <div class="price-aside">
            <div class="name-block">
                <div class="name">
                    <p>Fortuner</p>
                    <p>Ты настоящий</p>
                </div>
            </div>
            <div class="price-block">
                <div class="price-block-itm">
                    <p>Кредит в день от<br><span>304 ₽*</span></p>
                </div>
                <div class="price-block-itm">
                    <p>Выгода до<br><span>365 000 ₽*</span></p>
                </div>
                <div class="price-block-itm">
                    <p>Скидка по trade-in до<br><span>50 000 ₽*</span></p>
                </div>
                <div class="price-block-itm">
                    <p>В подарок<br><span>3 ТО</span></p>
                </div>
                <div class="price-block-itm">
                    <p>В подарок<br><span>зимние шины</span></p>
                </div>
            </div>
            <div class="test-drive-block">
                <div class="test-drive">
                    <img src="../assets/test-drive-pic.png" alt="">
                    <a href="#">Записаться на Тест-драйв</a>
                </div>
                <div class="offer-button">
                    <a href="#">Получить предложение</a>
                </div>
                <p>Нашли дешевле?</p>
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

    .name {
        background-image: url('../assets/name-bg.png');
        background-repeat: no-repeat;
        background-position: center center;
        background-size: cover;    
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
    }
    
</style>
