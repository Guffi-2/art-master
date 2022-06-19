<template>
  <div class="HelloWorld">
    <div class="center">
      <p></p>
      <p></p>
      <h1>UniFur</h1>
      <input placeholder="Почта" />
      <p></p>
      <p></p>
      <input placeholder="Пароль" type="password" />
      <p></p>
      <input type="submit" value="Войти" />
      <p></p>
      <p></p>
      <input
        type="submit"
        value="Регистрация"
        onclick="location.href='https://apple.com/'"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {};
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: #4a5059;
}
input {
  background-color: #4e4e4e;
  color: white;
  border-radius: 3px;
  border: none;
}
</style>