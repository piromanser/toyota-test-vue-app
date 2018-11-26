<template>
    <section>
        <div class="container">
            <h4>Специальные предложения</h4>
            <div class="special-offers-block">
                <div class="special-offers-itm">
                    <p>«Семейный автомобиль»</p>
                    <p><span>-10%</span><br> по госпрограмме</p>
                    <p>У вас большая семья<br>с двумя детьми и более?</p>
                    <a href="#">Получить</a>
                </div>
                <div class="special-offers-itm">
                    <p>«Персональные условия»</p>
                    <p>отдаём А/м<br>на уникальных<br>условиях</p>
                    <p>Отдаем а/м на уникальных условиях. Персональные бонусы и подарки от директора салона.</p>
                    <a href="#">Получить</a>
                </div>
                <div class="special-offers-itm">
                    <p>«Первый автомобиль»</p>
                    <p><span>-10%</span><br> по госпрограмме</p>
                    <p>Вы никогда раньше не владели автомобилем в собственности?</p>
                    <a href="#">Получить</a>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.special-offers-block {
    display: flex;
}

.special-offers-itm {
    flex: 1;
    background-color: #fdfdfd;
    display: flex;
    flex-direction: column;
    box-shadow: 0 8px 9px rgba(0, 0, 0, 0.2);
    padding: 5px;
}

.special-offers-itm a {
    margin-top: auto;
    margin-bottom: 0;
}

.special-offers-itm:not(:nth-child(2)) a {
    margin: auto auto 5px auto;
    margin-bottom: 0;
    text-decoration: none;
    letter-spacing: 0.08px;
    color: #ffffff;
    padding: 17px 42px 17px 42px;
    border-radius: 25px;
    background-color: #e50000;
    letter-spacing: 0.08px;
}

.special-offers-itm:nth-child(2) a {
    letter-spacing: 0.08px;
    color: #ffffff;
    border: 3px solid #ffffff;
    border-radius: 25px;
    margin: auto;
    text-decoration: none;
    padding: 17px 42px 17px 42px;

}


.special-offers-itm:not(:nth-child(2)) p:first-child {
    font-size: 24px;
    line-height: 36px;
    letter-spacing: 0.12px;
}

.special-offers-itm:not(:nth-child(2)) p:nth-child(2) {
    font-size: 24px;
    font-weight: 700;
    line-height: 36px;
    text-transform: uppercase;
    margin-bottom: 0;
    margin-top: 0;
}

.special-offers-itm:not(:nth-child(2)) p:nth-child(2) span {
    font-size: 48px;
    font-weight: bold;
    letter-spacing: -1.2px;
}

.special-offers-itm:nth-child(2) {
    background-image: url('../assets/unic-offer-bg.png');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    background-color: rgba(0, 0, 0, 0.5);
    margin: 0 60px 0 60px;
    color: #ffffff;
}

.special-offers-itm:nth-child(2) p:first-child {
    color: #ffffff;
    font-size: 24px;
    line-height: 36px;
    letter-spacing: 0.12px;
}

.special-offers-itm:nth-child(2) p:nth-child(2) {
    font-size: 24px;
    line-height: 36px;
    font-weight: 700;
    letter-spacing: 0.6px;
    text-transform: uppercase;
}

.special-offers-itm:nth-child(2) p:nth-child(3) {
    line-height: 24px;
    letter-spacing: 0.08px;
}

.special-offers-itm:not(:nth-child(2)) p:nth-child(3) {
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.08px;
}

h4 {
    font-size: 32px;
    font-weight: 700;
    letter-spacing: 0.16px;
    text-align: center;
    }
</style>



