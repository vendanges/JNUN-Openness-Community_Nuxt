<template>
  <main>
    <Header />
    <Tabs/>
    <Nuxt />
  </main>
</template>

<script>
  import Header from './Header'
  import Tabs from './components/tabs'

  export default {
    name: "Navigation",
    components: {
      Header,
      Tabs
    },
    data() {
      return {

      }
    },
    computed: {
      currentTabComponent: function () {
        return "tab-" + this.currentTab.toLowerCase()
      }
    }
  }
</script>

<style scoped>

</style>
