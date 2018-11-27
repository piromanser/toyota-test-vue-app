<template>
    <section>
        <div class="container">
            <h4>До конца действия акции осталось:</h4>
            <img src="../assets/section-stock-line.png" alt="">

            <div class="timer-wrapper">
                <div class="timer">
                    <div>
                        <span>{{ daysLeft }}</span>
                        <span>Дней</span>
                    </div>
                    <div>
                        <span>{{ hoursLeft }}</span>
                        <span>Часов</span>
                    </div>
                    <div>
                        <span>{{ minutesLeft }}</span>
                        <span>Минут</span>
                    </div>
                    <div>
                        <span>{{ secondsLeft }}</span>
                        <span>Секунд</span>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    data() {
        return {
            deadline: new Date(2019, 0, 1),
            timer: null,
            currentDatetime: new Date(),
        }
    },
    computed: {
        timeleftSecondsTotal() {
            return (this.deadline - this.currentDatetime) / 1000
        },
        daysLeft() {
            return Math.trunc(this.timeleftSecondsTotal / (60 * 60 * 24))
        },
        hoursLeft() {
            const remainingTime = this.timeleftSecondsTotal - (this.daysLeft * 60 * 60 * 24)
            return Math.trunc(remainingTime / (60 * 60))
        },
        minutesLeft() {
            const remainingTime = this.timeleftSecondsTotal - (this.daysLeft * 60 * 60 * 24) - (this.hoursLeft * 60 * 60)
            return Math.trunc(remainingTime / 60)
        },
        secondsLeft() {
            const remainingTime = this.timeleftSecondsTotal - (this.daysLeft * 60 * 60 * 24) - (this.hoursLeft * 60 * 60) - (this.minutesLeft * 60)
            return Math.trunc(remainingTime)
        },
    },
    created() {
        this.timer = setInterval(() => this.updateCurrentDatetime(), 1000)
    },
    destroyed() {
        clearInterval(this.timer)
    },
    methods: {
        updateCurrentDatetime() {
            this.currentDatetime = new Date()
        }
    }
}
</script>


<style lang="scss" scoped>
section {
    margin-bottom: 127px;
}

.container {
    text-align: center;
}

img:last-child {
    width: 100%;
}

h4 {
    font-size: 32px;
    font-weight: 700;
    line-height: 85.99px;
    letter-spacing: 0.16px;
    text-align: center;
    margin-bottom: 0;
}

.timer-wrapper {
    width: 100%;
    height: 399px;
    background-position: center;
    background-repeat: no-repeat;
    background-image: url('../assets/timer.jpg');
    display: flex;
    justify-content: center;
    align-items: center;
}
.timer {
    left: 0;
    top: 0;
    color: white;
    display: flex;

    > div {
        display: flex;
        flex-direction: column;

        > span:first-child {
            font-size: 140px;
            line-height: 1.1;
        }

        > span:last-child {
            font-size: 16px;
            font-weight: normal;
            text-transform: uppercase;
        }
    }

    > div:not(:last-child) {
        > span:first-child::after {
            content: ':';
            opacity: .5;
        }
    }
}
</style>
