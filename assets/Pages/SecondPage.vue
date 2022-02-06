<template>
  <div id="SecondPage">
    <h2>{{ title }}</h2>
    <navigator link="/page">Second page</navigator>
  </div>
</template>

<script>
import Navigator from "../Components/Navigator";

export default {
    name: 'SecondPage',
    components: {
        'navigator': Navigator
    },
    data() {
        return {
            title: "Second page"
        }
    },
    created() {
        window.document.title = this.title;
    },
}
</script>
