<template>
    <section>
        <div class="container">
            <div class="liked-block">
                <h4>Не нашли понравившийся автомобиль?</h4>
                <p>Возможно нужный вам автомобиль уже стоит на поставке и скоро будет в наличии.<br>Забронируйте его первым!</p>
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
                        <li>
                            <a href="#">Оставить заявку</a>
                        </li>
                    </ul>               
            </div>
            <div class="bg"></div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.container {
    display: flex;

}
.liked-block {  
    flex: 2;
}

.liked-list {
    display: flex;
    list-style: none;
    flex-direction: column;
    padding: 0;
}

li {
    display: flex;
}

.bg {
    background-image: url('../assets/liked-auto-bg.png');
    flex: 3;
}
</style>
