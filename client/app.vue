<template>
  <div id="app">
    <div id="cover" />
    <Header />
    <Todo />
    <Footer />
  </div>
</template>

<script>
import Header from './layout/header.vue'
import Footer from './layout/footer.jsx'
import Todo from './views/todos/todo.vue'

export default {
  components: {
    Header,
    Footer,
    Todo
  }
}
</script>

<style lang="stylus" scoped>
#app{
  position absolute
  left 0
  right 0
  top 0
  bottom 0
}
#cover{
  position absolute
  left 0
  top 0
  right 0
  bottom 0
  background-color #999
  opacity .5
  z-index -1
}
</style>
