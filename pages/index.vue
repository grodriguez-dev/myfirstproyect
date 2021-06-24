<template>
  <h1>Welcome to my first nuxt app</h1>
</template>

<script>
export default {
  head() {
    return {
      title: 'Application Nuxt Posts | home',
      meta: [
        {
          hid: "description",
          name: "description",
          content: "website about posts"
        }
      ],
      htmlAttrs: {
        lang: 'en'
      }
    }
  }
}
</script>