<template>
    <section>
        <div class="container">
            <div class="model-select-menu">
            <div><a href="#">Corolla</a></div>
            <div><a href="#">Camry</a></div>
            <div><a href="#">RAV4</a></div>
            <div><a href="#">Highlander</a></div>
            <div><a href="#">Land Cruiser Prado</a></div>
            <div><a href="#">Land Cruiser 200</a></div>
            <div><a href="#">Hilux</a></div>
            <div><a href="#">Fortuner</a></div>
            <div><a href="#">Prius</a></div>
        </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.model-select-menu {
    display: flex;
    justify-content: space-around;
    height: 69px;
}

.model-select-menu div {
    height: 100%;
    display: flex;
    align-items: center;
}

.model-select-menu a {
    text-decoration: none;
    font-size: 18px;
    color: #333333;
    letter-spacing: 0.09px;
    font-weight: 700;
    padding: 0 10px 0 10px;  
    line-height: 85.99px;
}

.model-select-menu div:hover {
    background-color: #e50000;
    a {
        color: #ffffff;
    }
}
</style>
