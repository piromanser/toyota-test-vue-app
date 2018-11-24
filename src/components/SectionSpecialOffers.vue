<template>
    <section>
        <div class="container">
            <h4>Специальные предложения</h4>
            <div class="special-offers-block">
                <div class="special-offers-itm">
                    <p>«Семейный автомобиль»</p>
                    <p>-10% по госпрограмме</p>
                    <p>У вас большая семья с двумя детьми и более?</p>
                    <a href="#">Получить</a>
                </div>
                <div class="special-offers-itm">
                    <p>«Персональные условия»</p>
                    <p>отдаём А/м на уникальных условиях</p>
                    <p>Отдаем а/м на уникальных условиях. Персональные бонусы и подарки от директора салона.</p>
                    <a href="#">Получить</a>
                </div>
                <div class="special-offers-itm">
                    <p>«Первый автомобиль»</p>
                    <p>-10% по госпрограмме</p>
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
}

.special-offers-itm:nth-child(2) {
    background-image: url('../assets/unic-offer-bg.png');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    background-color: rgba(0, 0, 0, 0.5)
}
</style>

