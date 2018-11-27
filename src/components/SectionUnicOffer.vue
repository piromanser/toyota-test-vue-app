<template>
    <section>
        <div class="container">
            <h4>Уникальное предложение!</h4>
            <img src="../assets/section-stock-line.png" alt="">
            <p>Получите максимально выгодные условия на покупку Toyota</p>
            <form action="" method="post">
                <input type="text" placeholder="Ваш номер телефона">
                <input type="button" name="take-offer" value="Получить предложение">
            </form>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    text-align: center;
    background-color: #f0f0f0;
    margin-bottom: 99px;
    padding: 35px 0 70px 0;
}

h4 {
    font-size: 32px;
    font-weight: 700;
    letter-spacing: 0.16px;
    line-height: 42.99px;
    margin: 0;
}

p {
    font-size: 24px;
    letter-spacing: 0.12px;
    line-height: 24px;
    margin-bottom: 50px;
}

form {
    position: relative;
}

form input {
    position: relative;
}

form input:first-child {
    box-shadow: 0 1px 3px 1px rgba(0, 0, 0, 0.1);
    border-radius: 25px;
    background-color: #ffffff;
    font-size: 16px;
    letter-spacing: 0.08px;
    opacity: 0.5;
    width: 400px;
    padding: 13px 26px 13px 26px;
    left: 10px;
}

form input:last-child {
    width: 230px;
    border-radius: 25px;
    background-color: #e50000;
    padding: 17px 26px 17px 26px;
    border: none;
    right: 30px;
    color: #ffffff;
    letter-spacing: 0.08px;
}
</style>
