<template>
  <PageMain>

  </PageMain>
</template>

<script>
import PageMain from './components/PageMain.vue'

export default {
  name: 'App',
  components: {
    PageMain
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
}

.container {
  margin: 0 auto;
  max-width: 1170px;
  padding: 0 12px;
}

.button {
  font-family: Roboto;
  font-size: 20px;
  font-weight: 400;
  line-height: 23.44px;
  text-align: left;
  padding: 8px 15px;
  background-color: #A5C7F9;
  color: #FFFFFF;
  border: none;
  border-radius: 5px;
}

button:active {
  animation-timing-function: ease-out;
  animation-duration: 300ms;
  background: #2c3e50;
}



</style>
