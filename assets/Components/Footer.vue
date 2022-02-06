<template>
  <header>
    <h1>{{ test }}</h1>
  </header>
</template>

<script>
  export default {
    name: 't-footer',
    data() {
      return {
        test: "footer",
      };
    },
    created() {
      console.log(this.test);
    }
  }
</script>
