<template>
  <div class="border-b-2 border-blue-500 h-full py-4">
      <nuxt-link :to="link">
          {{ title }}
      </nuxt-link>
  </div>
</template>

<script>
export default {
    name: 'NavigationMenuItem',
    props: [
        'title', 'link'
    ]
}
</script>

<style>

</style>