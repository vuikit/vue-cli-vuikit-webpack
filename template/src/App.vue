<template>
  <div id="app" class="uk-container uk-container-center uk-text-center uk-margin-large-top">
    <img src="./assets/logo.png">
    <h1>\{{ msg }}</h1>
    <ul class="uk-subnav uk-flex-center">
      <li><a href="https://vuikit.js.org" target="_blank">Docs</a></li>
      <li><a href="https://gitter.im/vuikit/vuikit" target="_blank">Gitter Chat</a></li>
      <li><a href="https://twitter.com/vuikit" target="_blank">Twitter</a></li>
    </ul>
    <vk-button>Hello from Vuikit button!</vk-button>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue Vuikit App'
    }
  }
}
</script>
