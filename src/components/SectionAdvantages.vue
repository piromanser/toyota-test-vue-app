<template>
    <section>
        <h4>Наши преимущества</h4>
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
}
</style>
