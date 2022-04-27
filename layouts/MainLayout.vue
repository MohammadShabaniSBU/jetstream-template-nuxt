<template>
  <div class="w-screen h-screen overflow-auto bg-gray-100" dir="rtl">
      <navigation-menu />
      <div v-if="$slots.header">
        <header class="bg-white shadow">
            <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
                <slot name="header" />
            </div>
        </header>
      </div>
      <div class="px-48 py-12">
          <div class="bg-white rounded-lg shadow-md p-12">
              <slot />
          </div>
      </div>

  </div>
</template>

<script>
import NavigationMenu from '~/components/NavigationMenu.vue'
export default {
    components: { NavigationMenu },
}
</script>

<style>

</style>