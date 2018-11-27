<template>
    <section>
        <div class="container">
            <h4>Контакты</h4>
            <img src="../assets/section-stock-line.png" alt="">
            <div class="contacts-block">
                <div class="contact-itm">
                    <img src="../assets/contacts-pic1.png" alt="">
                    <div>
                        <p>Телефон</p>
                        <p class="tel">+7 (351) 211-10-10</p>
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
    section {
        margin-bottom: 60px;
    }
    
    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .container>img {
        margin-bottom: 61px;
    }
    
    h4 {
        text-align: center;
        font-size: 32px;
        font-weight: 700;
        line-height: 85.99px;
        letter-spacing: 0.16px;
        margin: 0;
    }

    .contacts-block {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
    }

    .contact-itm {
        display: flex;
        flex: 1;
        padding: 10px;
    }

    .contact-itm img {
        width: 50px;
        height: 50px;
        margin: 6px 14px 6px 6px;
    }

    .contact-itm>div>p:first-child {
        font-size: 24px;
        font-weight: 700;
        line-height: 32px;
        letter-spacing: 0.12px;
        margin: 0;
    }

    .contact-itm>div>p:last-child {
        font-size: 24px;
        line-height: 32px;
        letter-spacing: 0.12px;

    }

    .tel {
        border-bottom: 1px solid #333333;;
    }
</style>
