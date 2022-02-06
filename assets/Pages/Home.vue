<template>
  <div id="home">
    <h2>{{ title }}</h2>
    <navigator link="/page">Home</navigator>
  </div>
</template>

<script>
import Navigator from "../Components/Navigator";

export default {
  name: 'Home',
  components: {
    'navigator': Navigator
  },
  data() {
    return {
      title: "Home"
    }
  },
  created() {
    window.document.title = this.title;
  },
}
</script>
