<template>
  <div>
    <app-header></app-header>
    <router-view></router-view>
  </div>
</template>

<script>
import header from './components/header.vue'
import addBlog from './components/addBlog.vue'
import showBlogs from './components/showBlogs.vue'
import singleBlog from './components/singleBlog.vue'

export default {
  components: {
    'app-header': header,
    'add-blog': addBlog,
    'show-blogs': showBlogs,
    'single-blog': singleBlog
  },
  data () {
    return {
      
    }
  },
  methods: {
    
  }
}
</script>

<style>
#app{
  margin: 0;
  font-family: 'Nunito SemiBold';
}
</style>
