<template>
  <div>
    <h1>{{ pageContent.title }}</h1>
    <a href="/test">Now refresh the page</a> - Will see an error in the console
  </div>
</template>

<script>
export default {
  asyncData() {
    // Real data would be obtained from CMS
    return {
      pageContent: {
        title: 'Via generic route to _page',
      },
    }
  },
}
</script>
