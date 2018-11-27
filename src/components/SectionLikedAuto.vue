<template>
    <section>
        <div class="container">
            <div class="liked-block">
                <h4>Не нашли<br>понравившийся автомобиль?</h4>
                <img src="../assets/section-stock-line.png" alt="">
                <p>Возможно нужный вам автомобиль уже стоит на поставке и скоро будет в наличии.<br><br>Забронируйте его первым!</p>
                    <ul class="liked-list">
                        <li>
                            <img src="../assets/liked-pic1.png" alt="">
                            <p>А/м, которых еще нет в шоуруме.</p>
                        </li>
                        <li>
                            <img src="../assets/liked-pic2.png" alt="">
                            <p>Большой выбор комплектаций</p>
                        </li>
                        <li>
                            <img src="../assets/liked-pic3.png" alt="">
                            <p>Персональная консультация</p>
                        </li>
                        <li class="btn">
                            <a href="#">Оставить заявку</a>
                        </li>
                    </ul>               
            </div>
            <div class="bg"></div>
        </div>
        <div class="bg"></div>
    </section>
</template>

<style lang="scss" scoped>
.container {
    display: flex;
    font-size: 18px;

}
.liked-block {  
    flex: 2;
}

.liked-block>p {
    font-weight: 400;
    letter-spacing: 0.09px;
    line-height: 26px;
}

.liked-list {
    display: flex;
    list-style: none;
    flex-direction: column;
    padding: 0;
    margin-top: 26px;

}

.liked-list li {
    display: flex;
    align-items: center;
    margin-bottom: 40px;
}

.liked-list p {
    font-weight: 700;
    line-height: 40px;
    letter-spacing: 0.09px;
    margin-left: 5px;
    margin: 0 0 0 10px;
}

.liked-list img {
    width: 50px;
    height: 50px;
}

.bg {
    background-image: url('../assets/liked-auto-bg.png');
    flex: 3;
}

h4 {
    font-size: 32px;
    font-weight: 700;
    line-height: 40px;
    letter-spacing: 0.16px;
    margin-bottom: 0;
}

.btn {
    border-radius: 25px;   
    padding: 17px 37px 17px 37px;
    background-color: #e50000;
    display: flex;
    width: 50%;
}

.btn a {
    text-decoration: none;
    color: #ffffff;
    letter-spacing: 0.08px;
    text-align: center;
    margin: auto;
}
</style>
