<template>
  <div class="top">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Top',
  data () {
    return {
      msg: process.env.API_URL
    }
  }
}
</script>
