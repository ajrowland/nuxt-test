<template>
  <div>
    <h1>{{ pageContent.title }}</h1>
    <nuxt-link to="/test">Now try via generic route</nuxt-link>
  </div>
</template>

<script>
export default {
  asyncData() {
    // Real data would be obtained from CMS
    return {
      pageContent: {
        title: 'Via index file route',
      },
    }
  },
}
</script>
