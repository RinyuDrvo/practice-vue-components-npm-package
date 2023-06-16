<template>
  <div>
    <h1>このプロジェクトはVueコンポーネントのnpmパッケージ化学習用です</h1>
    <my-button>ボタン</my-button>
  </div>
</template>

<script>
import MyButton from "./MyButton.vue";

export default {
  name: "HelloWorld",
  components: {
    MyButton,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
