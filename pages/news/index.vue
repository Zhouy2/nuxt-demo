<template>
  <div>
    <p>newsId: {{$route.params.newsId}}</p>
    <h2>News Index page</h2>
    <ul>
      <li><nuxt-link :to="{name:'index'}">HOME</nuxt-link></li>
      <li><nuxt-link :to="{name:'news-id',params:{id:123}}">news-1</nuxt-link></li>
      <li><a href="/news/jspang">news-2</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  transition: 'test'
}
</script>

