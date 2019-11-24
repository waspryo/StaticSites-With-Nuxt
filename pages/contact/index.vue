<template>
<div class="container">
  <div class="title">contact page</div>
  <span class="subtitle">This is a subtitle</span>
  </div>
</template>

<script>
export default {
  layout: "contact-layout",
  head() {
    return {
      title: 'Contact page',
      meta: [
        {hid: 'description', name: 'description', content: 'My description'},
        {hid: 'ogtitle', property: 'og:title', content: 'Contact page'}
      ]
    }
  }
};
</script>

<style lang="scss">
@import "assets/scss/variables";


  .container {
    width: 960px;
    margin: 40px auto;
    background: $blue;

    .title {
      font-size: 36px;
    }
    .subtitle {
      display: block;
      font-size: 18px;
    }
  }
</style>