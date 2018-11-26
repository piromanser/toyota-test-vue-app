<template>
  <div>
    <div class="shadow"></div>

    <div class="modal">
      <button class="modal__close" @click="$emit('closeModal')"></button>

      <header>
        <h3 style="margin: 0;">Узнать цену</h3>
        <div style="display: inline-block;" class="red-line"></div>
        <p>Заполните форму ниже, чтобы узнать цену автомобиля</p>
      </header>

      <form class="form" @submit.prevent="onSumbit">
        <input v-model="formName" class="form__input form__input_text" type="text" placeholder="Имя">
        <input v-model="formPhone" class="form__input form__input_text" type="text" placeholder="Телефон">

        <button class="button button_request-price">Узнать цену</button>

        <label>
          <input type="checkbox">
           Я согласен с условиями обработки персональных данных
        </label>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      formName: '',
      formPhone: '',
    }
  },
  methods: {
    onSumbit() {
      alert(`
        Узнаем цену...
        Имя: ${this.formName}
        Телефон: ${this.formPhone}
      `)
      this.$emit('closeModal')
    }
  }
}
</script>


<style lang="scss" scoped>
.red-line {
  width: 80px;
  height: 3px;
  background-color: #e50000;
  opacity: 0.5;
}

header {
  text-align: center;
}

.modal {
  position: fixed;
  padding: 50px;
  box-sizing: border-box;
  left: 50%;
  top: 50%;
  width: 500px;
  height: 430px;
  margin-left: -250px;
  margin-top: -215px;
  background: white;
  border-radius: 10px;

  &__close {
    position: absolute;
    margin: 0;
    border: 0;
    top: 10px;
    right: 10px;
    width: 10px;
    height: 10px;
    padding: 10px;
    cursor: pointer;
    background-position: center;
    background-repeat: no-repeat;
    background-color: transparent;
    background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAKCAYAAACNMs+9AAAAmklEQVQoU23QwQrDIAwG4NliKx27CcI81DfoBjuUvf9xsPUNvArexoqttIwULGnQU0w+8ousba/PEJbBOfc7ZY5S6ixE2TEo6rq8T9PyphjPGCzJYdrbIMVwpyk7xBhq+pQDlFJemqbqAI7jPHjvvylxhwkVRfWC4brOD4w3iJG1NkDPGCMwZjmU4jBmWuuec/5Jm+ifA44x3v4o+HG/oIZHWAAAAABJRU5ErkJggg==');
  }
}

.button {
  border: none;
  padding: 0;
  margin: 0;
  cursor: pointer;

  &_request-price {
    width: 240px;
    height: 50px;
    border-radius: 25px;
    background-color: #ce0000;
    font-size: 16px;
    color: #ffffff;
    letter-spacing: 0.08px;
    margin: 10px auto;
  }
}

.form {
  display: flex;
  flex-direction: column;

  &__input {
    margin-top: 10px;
    margin-bottom: 10px;

    &_text {
      height: 40px;
      line-height: 40px;
      border-radius: 3px;
      border: 1px solid #afafaf;
      box-shadow: inset 0 0 5px 1px rgba(0, 1, 5, 0.1);
    }
  }
}

.shadow {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: rgba(0, 0, 0, .75);
}
</style>
