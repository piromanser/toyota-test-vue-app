<template>
    <section>
        <div class="container">
            <h4>Контакты</h4>
            <div class="contacts-block">
                <div class="contact-itm">
                    <img src="../assets/contacts-pic1.png" alt="">
                    <div>
                        <p>Телефон</p>
                        <p>+7 (351) 211-10-10</p>
                    </div>
                </div>
                <div class="contact-itm">
                    <img src="../assets/contacts-pic2.png" alt="">
                    <div>
                        <p>Адрес</p>
                        <p>г. Челябинск, Черкасская улица, 19</p>
                    </div>
                </div>
                <div class="contact-itm">
                    <img src="../assets/contacts-pic3.png" alt="">
                    <div>
                        <p>Режим работы</p>
                        <p>с 9:00 до 21:00 ежедневно</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    h4 {
        text-align: center;
    }

    .contacts-block {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
    }

    .contact-itm {
        display: flex;
    }

</style>
