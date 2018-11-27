<template>
    <section>
        <h4>Наши преимущества</h4>
        <img src="../assets/section-stock-line.png" alt="">
        <p>Преимущества покупки а/м в нашем салоне</p>
        <div class="container">           
            <div class="advantages-column">
                <div class="advantages-itm">
                    <img src="../assets/advantages-pic1.png" alt="">
                    <p>Официальный дилер Toyota</p>
                </div>
                <div class="advantages-itm">
                    <img src="../assets/advantages-pic4.png" alt="">
                    <p>Привлекательные программы для постоянных клиентов</p>
                </div>
            </div>
            <div class="advantages-column">
                <div class="advantages-itm">
                    <img src="../assets/advantages-pic2.png" alt="">
                    <p>Большой склад а/м в наличии</p>
                </div>
                <div class="advantages-itm">
                    <img src="../assets/advantages-pic5.png" alt="">
                    <p>Нашими партенерами являются ведущие банки и страховые компании</p>
                </div>
            </div>
            <div class="advantages-column">
                <div class="advantages-itm">
                    <img src="../assets/advantages-pic3.png" alt="">
                    <p>Персональные условия покупки</p>
                </div>                                
                <div class="advantages-itm">
                    <img src="../assets/advantages-pic6.png" alt="">
                    <p>Обмен вашего автомобиля на новый Toyota «день в день»</p>
                </div>
            </div>                        
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    text-align: center;
    margin-bottom: 90px;
}

.container {
    display: flex;
}

.advantages-column {
    display: flex;
    flex-direction: column;   
}

.advantages-itm {
    display: flex;
    align-items: flex-start;
    padding: 10px;
}

.advantages-itm img {
    width: 30px;
    height: 30px;
}

.advantages-itm p {
    margin: 0 10px 90px 30px;
    text-align: left;
    font-size: 24px;
    line-height: 32px;
    letter-spacing: 0.12px;
}

h4 {
    color: #333333;
    font-size: 32px;
    line-height: 85.99px;
    letter-spacing: 0.16px;
    margin-top: 100px;
}

section>p {
    line-height: 24px;
    letter-spacing: 0.08px;
    margin-bottom: 90px;
}
</style>
