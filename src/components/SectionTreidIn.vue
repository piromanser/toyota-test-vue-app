<template>
    <section>
        <div class="container">
            <div class="trade-in-block">
                <h4>Выгодные условия Treid-in</h4>

                <ul>
                    <li>
                        <p>Экспресс-оценка вашего автомобиля</p>
                        <p>Наши специальсты быстро и профессионально оценят ваш автомобиль. Деньги в день обращения.</p>
                    </li>
                    <li>
                        <p>Честная цена</p>
                        <p>Мы предлагаем честную и аргументированную цену, отвечающую объективной рыночной стоимости.</p>
                    </li>
                    <li>
                        <p>Быстрое оформление и диагностика</p>
                        <p>Быстрая диагностика и оформление всех необходимых документов для сделки купли-продажи.</p>
                    </li>
                    <li>
                        <p>Обмен старого автомобиля на новый</p>
                        <p>Для обмена старого авто на новый по программе Trade-in - требуется не более 1 часа.</p>
                    </li>
                </ul>

                <p>Закажите предварительную онлайн оценку автомобиля</p>
                <a href="#">Заказать оценку</a>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    // height: 1080px;
    padding-top: 300px;
    padding-bottom: 100px;
}

ul {
    list-style: none;

    li {
        position: relative;
        
        &::before {
            content: "";
            display: block;
            width: 15px;
            height: 15px;
            background: red;
            border-radius: 50%;
            position: absolute;
            left: -20px;
            top: 0;
        }
    }
}

section {
    background-image: url('../assets/treid-in-bg.png');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
}

.trade-in-block {
    background-color: rgba(0, 0, 0, 0.7);
    width: 550px;
    color: #ffffff;
    margin-left: auto;
    padding: 5px;
    display: flex;
    flex-direction: column;
}

.trade-in-block > p {
    font-size: 24px;
    font-weight: 700;
    line-height: 30px;
    letter-spacing: 0.12px;
    text-align: center;
}

.trade-in-block ul li p:first-child {
    font-size: 18px;
    font-weight: 700;
    line-height: 18px;
    letter-spacing: 0.09px;
}

.trade-in-block ul li p:last-child {
    font-size: 16px;
    font-weight: 400;
    line-height: 19.2px;
    letter-spacing: 0.08px;
}

h4 {
    font-size: 32px;
    text-align-last: center;
    font-weight: 700;
    line-height: 19.2px;
    letter-spacing: 0.16px;
    margin: 10px;
}

.trade-in-block a {
    margin: auto;
    letter-spacing: 0.08px;
    border-radius: 25px;
    background-color: #e50000;
    padding: 17px 37px 17px 37px;
    color: #ffffff;
    text-decoration: none;
}
</style>

