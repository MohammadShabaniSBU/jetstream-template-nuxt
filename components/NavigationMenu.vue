<template>
  <div class="w-full  bg-white shadow px-48 border-b flex items-center">
      <logo class="w-10 max-h-10 ml-6" />
      <div class="flex gap-6">
          <navigation-menu-item title="خانه" link="/login" />
      </div>
  </div>
</template>

<script>
import Logo from './Logo.vue'
import NavigationMenuItem from './NavigationMenuItem.vue'
export default {
  components: { Logo, NavigationMenuItem },

}
</script>

<style>

</style>