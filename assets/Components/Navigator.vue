<template>
    <router-link :to='link'><slot></slot></router-link>
</template>

<script>
  export default {
    props: {
      link: String,
    },
  }
</script>
