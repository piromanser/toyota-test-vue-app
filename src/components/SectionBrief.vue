<template>
<section>
  <div class="container">
    <div class="brief-block">
        <div class="sub-block">
            <img src="../assets/brief-pic.png" alt="">
            <p>100</p>       
        </div>
    <p>Автомобилей в наличии</p>
    </div>
    <div class="brief-block">
        <div class="sub-block">
            <img src="../assets/brief-pic.png" alt="">
            <p>10</p>         
        </div>
    <p>Бонусных программ</p>
    </div>
    <div class="brief-block">
        <div class="sub-block">
            <img src="../assets/brief-pic.png" alt="">
            <p>1000</p>         
        </div>
    <p>довольных клиентов</p>
    </div>
    <div class="brief-block">
        <div class="sub-block">
            <img src="../assets/brief-pic.png" alt="">
            <p>45</p>
        </div>
    <p>ДЦ по всей россии</p>
    </div>
  </div>
</section>
</template>

<style lang="scss" scoped>
section {
    margin-bottom: 74px;
}

.container {
    background-image: url('../assets/brief-bg.png');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    display: flex;
    justify-content: center;
    color: #ffffff;
    text-align: center;
    text-transform: uppercase;
    font-size: 50px;
    line-height: 19.2px;
    letter-spacing: 0.25px;
    height: 320px;
}

.brief-block {
    display: flex;
    flex-direction: column;
    margin: 20px; 
    justify-content: center; 
}

.brief-block p {
    margin: 0;
}

.sub-block {
    display: flex;
    justify-content: center;
    align-items: center;
}

.sub-block img {
    width: 24px;
    height: 36px;
}

.brief-block>p {
    font-size: 18px;
    line-height: 24px;
    letter-spacing: 0.09px;


}
</style>
