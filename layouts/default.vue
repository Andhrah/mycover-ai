<script>
import Button from '~/components/Button.vue'

export default {
  components: {
    Button,
  }
}
</script>

<template>
  <nav class="bg-[#FFFFFF] flex px-36 h-[5.5rem] items-center justify-between shadow-sm mb-px fixed w-screen">
    <img src="~/assets/images/mycover_logo.png" alt="logo" class="h-10 w-[10.375rem]">
    <ul class="flex justify-between w-[45%]">
      <li><NuxtLink to="/" aria-label="Products">Products</NuxtLink></li>
      <li><NuxtLink to="/about" aria-label="Solutions">Solutions</NuxtLink></li>
      <li><NuxtLink to="/contact" aria-label="Developers">Contact</NuxtLink></li>
      <li><NuxtLink to="/contact" aria-label="Company">Company</NuxtLink></li>
      <li><NuxtLink to="/contact" aria-label="Learn">Learn</NuxtLink></li>
    </ul>

    <div class="flex justify-between w-[24%]">
      <Button class="bg-[#F2F4F7] text-[#475467]">Login</Button>
      <Button class="text-[#FFFFFF]">Get Started</Button>
    </div>
  </nav>
  <slot />
</template>
