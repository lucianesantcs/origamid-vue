<template>
  <div id="app">
    <Header />
    <router-view class="container"></router-view>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
export default {
  components: {
    Header,
  },
};
</script>>

<style>
body {
  margin: 0;
  padding: 0;
  font-family: "Avenir", Arial, Helvetica, sans-serif;
  color: #234;
}

ul {
  padding: 0;
  margin: 0;
}

li {
  list-style: none;
}

a {
  font-weight: bold;
  text-decoration: none;
  color: #234;
}

a.router-link-active {
  color: #4b8;
}

img {
  max-width: 100%;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.v-enter {
  opacity: 0;
  transform: translate3d(-20px, 0, 0);
}

.v-enter-active {
  transition: all 0.3s;
}

.conteudo {
  display: grid;
  grid-template-columns: 1fr minmax(200px, 400px);
  grid-gap: 30px;
}

@media screen and (max-width: 400px) {
  .conteudo {
    display: block;
  }
}
</style>
