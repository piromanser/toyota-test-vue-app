<template>
    <div class="container">
        <div class="stock-block">
            <div class="stock-itm">
                <img src="../assets/stock-pic.png" alt="">
            </div>
            <div class="stock-caption stock-itm">
                <h6>Fortuner</h6>
                <p>Год выпуска: 2016</p>
                <p>Двигатель: 1,6 МТ (110 л.с.)</p>
                <p>КПП: Механическая</p>
                <p>Привод: Передний привод</p>
                <p>Цвет: Серый металлик</p>
            </div>
            <div class="stock-price stock-itm">
                <p>Выгода до<span>100 500 ₽</span></p>
                <p>в кредит от<span>5 000 ₽/мес</span></p>
                <p style="font-size: 18px; font-weight: 700;"><span style="margin-right: 10px; opacity: 0.7; font-size: 16px; letter-spacing: 0.08px; color: #333333; text-transform: none; margin: 0;">Подробнее:</span>+7 (351)211-10-10</p>                
                <button class="button button_request-price" @click="$emit('requestPrice')">Узнать цену</button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.button {
  border: none;
  padding: 0;
  margin: 0;
  cursor: pointer;

  &_request-price {
    width: 240px;
    height: 50px;
    border-radius: 25px;
    background-color: #ce0000;
    font-size: 16px;
    color: #ffffff;
    letter-spacing: 0.08px;
    margin: 10px auto;
  }
}

.container {
    padding: 0;
}

.stock-block {
    display: flex;
    justify-content: space-around;
}

.stock-itm {
    flex: 1;
    padding: 7px;
}

.stock-itm:first-child {
    display: flex;
    align-items: center;
}

.stock-caption h6 {
    font-size: 24px;
    font-weight: 700;
    letter-spacing: 0.12px;
    margin: 0 0 27px 0;
}

.stock-caption p {
    font-size: 18px;
    font-weight: 400;
    letter-spacing: 0.09px;
    margin: 0 0 17px 0;
}

.stock-price {
    display: flex;
    flex-direction: column;
}

.stock-price p {
    font-size: 14px;
    font-weight: 700;
    letter-spacing: 0.07px;
    text-transform: uppercase;
}

.stock-price span {
    font-size: 24px;
    font-weight: 700;
    letter-spacing: 0.12px;
    color: #e50000;
    margin-left: 5px;;
}

.stock-price a {
    padding: 17px 80px 17px 80px;
    color: #ffffff;
    text-align: center;
    font-size: 16px;
    text-decoration: none;
    letter-spacing: 0.08px;
    background-color: #e50000;
    border-radius: 25px;  
}

</style>


