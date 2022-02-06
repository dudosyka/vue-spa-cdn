<template>
    <header>
        <h1>{{ test }}</h1>
    </header>
</template>

<script>
  export default {
    name: 't-header',
    data() {
      return {
        test: "header",
      };
    },
    created() {
      console.log(this.test);
    }
  }
</script>

