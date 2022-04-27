<template>
  <auth-layout>
    <div class="flex justify-center">
        <logo class="w-20"/>
    </div>
    <div class="bg-white rounded-md p-4 shadow-md space-y-3 text-gray-700">
        <div>
            <label class="label" for="">نام</label>
            <input type="text" class="input">
        </div>
        <div>
            <label class="label" for="">ایمیل</label>
            <input dir="ltr" type="text" class="input">
        </div>
        <div>
            <label class="label" for="">رمز عبور</label>
            <input type="password" class="input">
        </div>
        <div>
            <label class="label" for="">تایید رمز عبور</label>
            <input type="password" class="input">
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
