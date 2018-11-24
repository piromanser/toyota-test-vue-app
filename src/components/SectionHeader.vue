<template>
    <section>
        <div class="container">
            <div class="header-menu">
                <img class="header-menu-itm header-logo" src="../assets/logo.png" alt="logo">
                <a class="header-menu-itm" href="#">Автомобили в наличии</a>
                <a class="header-menu-itm" href="#">Предзаказ автомобиля</a>
                <a class="header-menu-itm" href="#">Записаться на тест-драйв</a>
                <a class="header-menu-itm" href="#">Treid-in</a>
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
    justify-content: space-around;
}

h2 {
    color: green;
}

.header-menu {
    display: flex;
    align-items: center;
    
}

.header-menu-itm {
    margin-left: 20px;
}

.header-logo {
    width: 60px;
    height: 50px;
}

.tel p {
margin: 0;
}
</style>
