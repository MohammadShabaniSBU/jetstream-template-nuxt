<template>
  <auth-layout>
    <div class="flex justify-center">
        <logo class="w-20"/>
    </div>
    <div class="bg-white rounded-md p-4 shadow-md space-y-3 text-gray-700">
        <div>
            <label class="label" for="">ایمیل</label>
            <input type="text" class="border border-gray-300 rounded-md p-2 w-full focus:border-blue-300 focus:outline-none focus:ring-2">
        </div>
        <div>
            <label class="label" for="">رمز عبور</label>
            <input type="text" class="border border-gray-300 rounded-md p-2 w-full focus:border-blue-300 focus:outline-none focus:ring-2">
        </div>
        <div>
            <input type="checkbox" id="rememberme">
            <label for="rememberme" class="text-sm">مرا بخاطر بسپار</label>
        </div>
        <div class="flex">
            <button class="px-4 py-1 bg-gray-900 text-gray-100 rounded-md">
                ورود        
            </button>
        </div>
    </div>
  </auth-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import AuthLayout from '~/layouts/AuthLayout.vue'
export default {
  components: { AuthLayout, Logo },

}
</script>
