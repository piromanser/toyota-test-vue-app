<template>
 <section>   
    <div class="container">
        <div class="variations-block">
           <div class="variations-header">
                <p>01</p>
                <p>Цена, как для сотрудника</p>
            </div>
            <p>Отдаем а/м по закрытому прайсу, как для сотрудника ДЦ. Предложение ограничено. Спешите.</p>
        </div>
        <div class="variations-block">
            <div class="variations-header">
                <p>02</p>
                <p>Улучшим предложение</p>
            </div>
            <p>Уже получили предложение по цене в другом салоне? Не спешите, - Мы его улучшим! </p>
        </div>
        <div class="variations-block">
            <div class="variations-header">
                <p>03</p>
                <p>Бронь а/м из поставки</p>
            </div>
            <p>Бронируйте лучшие а/м еще до поступления в салон. Пока вы думаете - другие покупают.</p>
        </div>
        <div class="variations-block">
            <div class="variations-header">
                <p>04</p>
                <p>Льготный кредит</p>
            </div>
            <p>Оформите кредит на выгодных условиях. Низкие ставки. Нет скрытых платежей.</p>  
        </div>
    </div>
 </section>
</template>

<style lang="scss" scoped>
section {
    background-color: #333333;
}

.container {
    display: flex;
    color: #ffffff;
}

.variations-header {
    display: flex;
    align-items: center;
}

.variations-header p {
    margin: 0;
    color: #ffffff;
    margin-bottom: 20px;
}

.variations-header p:first-child {
    font-size: 50px;
    opacity: 0.2;
    line-height: 53.28px;
    text-transform: uppercase;
    letter-spacing: 0.56px;
    font-weight: 700;
}

.variations-header p:last-child {
    font-size: 18px;
    font-weight: 700;
    line-height: 24px;
    letter-spacing: 0.45px;
    text-transform: uppercase;
    margin-left: 9px;
    }

.variations-block {
    flex: 1;
    padding: 10px;
}

.variations-block>p {
    font-size: 14px;
    color: #ffffff;
    line-height: 18px;
    letter-spacing: 0.07px;
    margin-bottom: 0;
}


.variations-block:not(:first-child) {
    border-left: 2px solid;
    border-color: rgba(255, 255, 255, 0.2)
    
}

.variations-block:hover {
    background-color: #e50000;
    color: #ffffff;
}

.variations-block:hover p:first-child {
    opacity: 1;
}


</style>

