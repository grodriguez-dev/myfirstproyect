<template>
    <div>
        <h1>About Us</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate tempore temporibus aliquam maxime, corporis iste aperiam laborum, earum mollitia perferendis inventore laudantium, voluptas necessitatibus fuga officiis quos maiores reiciendis facilis!</p>
    </div>
</template>

<script>
export default {
    head() {
    return {
      title: 'Posts | Nuxt application',
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