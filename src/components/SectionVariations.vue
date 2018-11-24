<template>
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
</template>

<style lang="scss" scoped>
.container {
    display: flex;
    background-color: #333333;
    color: #ffffff;
}

.variations-header {
    display: flex;
}

.variations-block {
    flex: 1;
}

.variations-block:not(:first-child) {
    border-left: #ffffff solid 2px;
}
</style>

