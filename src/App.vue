<template>
  <div id="app">
    <vue-multiple-themes
        :defaultTheme="'light'"
        :themeColorList="[
        'light',
        'dark',
        'sepia'
        ]"
        :changeThemeOff="true"
    >
    </vue-multiple-themes>
    <h1 class="app-title">Vue.js Multiple theme sample</h1>
    <div class="app-subtitle">You can use css class for color mode!</div>
    <ul>
      <li><a class="app-title" target="_blank" href="https://github.com/pooyagolchian/vue-multiple-themes">Github</a></li>
      <li><a class="app-title" target="_blank" href="https://www.npmjs.com/package/vue-multiple-themes">NPM</a></li>
      <li><a class="app-title" target="_blank" href="https://github.com/pooyagolchian/vue-multiple-theme-sample">Sample source code</a></li>
    </ul>

  </div>
</template>

<script>

import VueMultipleThemes from 'vue-multiple-themes'

export default {
  name: 'App',
  components: {
    VueMultipleThemes
  }
}
</script>

<style>
html {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  overflow: hidden;
  text-align: center;
}

ul {
  display: flex;
  justify-content: center;
  align-items: center;
}
li {
  padding: 0 10px;
  margin: 0;
  list-style: none;
}

.change-theme-box {
  font-size:30px !important;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>

