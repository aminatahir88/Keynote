<template>
  <div id="app">
    <HelloWorld />
    <WebsiteView/>
    <WebsitelistView/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import WebsiteView from './components/WebsiteView.vue'
import WebsitelistView from './components/WebsitelistView.vue'

export default {
  components: {
    HelloWorld,
    WebsiteView,
    WebsitelistView
  }
}
</script>

