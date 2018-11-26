<template>
    <section>
        <div class="container">
            <div class="header-menu">
                <img class="header-menu-itm header-logo" src="../assets/logo.png" alt="logo">
                <div class="header-menu-itm"><a href="#">Автомобили в наличии</a></div>
                <div class="header-menu-itm"><a href="#">Предзаказ автомобиля</a></div>
                <div class="header-menu-itm"><a href="#">Записаться на тест-драйв</a></div>
                <div class="header-menu-itm"><a href="#">Treid-in</a></div>
            </div>
            <div class="tel">
                <p>Официальный дилер Toyota</p>
                <a href="#">+7 (351)211-10-10</a>
            </div>
        </div>   
    </section>
</template>

<style lang="scss" scoped>
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

h2 {
    color: green;
}

.header-menu {
    display: flex;
    align-items: center;  
    height: 70px; 
}

.header-menu div {
    height: 100%;
}

.header-menu-itm {
    display: flex;
    align-items: center;
}

.header-menu-itm:not(:first-child) {
    margin-left: 10px;
    padding: 0 10px 0 10px;  
}

.tel p {
margin: 0;
}

.tel a {
    text-decoration: none;
    color: #e50000;
    margin: auto;
}

.tel  {
    text-align: right;
    font-weight: 700;

}

.header-menu a {
    font-size: 16px;
    color: #333333;
    font-weight: 400;
    text-decoration: none;
}

.header-menu-itm:not(:first-child):hover {
    color: #ffffff;
    background-color: #e50000;
}

.header-logo {
    width: 60px;
    height: 50px;
    margin: 10px;
    margin: 0;
}
</style>
