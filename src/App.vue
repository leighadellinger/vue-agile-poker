<template>
  <div id="app">
      <Header />
      <PokerCards title="Welcome to Your Vue.js Planning Poker App"/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import PokerCards from './components/PokerCards.vue'

export default {
  name: 'app',
  components: {
    Header,
    PokerCards
  }
}
</script>
