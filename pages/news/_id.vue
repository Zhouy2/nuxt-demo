<template>
  <div>
    <h2>News-content</h2>
    <p>NewsId:{{$route.params.id}}</p>
    <ul>
      <li><nuxt-link :to="{name:'index'}">Home</nuxt-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  validate({params}){
    return /^\d+$/.test(params.id);
  }
}
</script>