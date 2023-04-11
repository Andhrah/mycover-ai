<script>
export default {
  props: {
    type: {
      type: String,
      default: 'button'
    }
  }
}
</script>

<template>
  <button class="bg-[#47BFA3] rounded-lg h-12 px-8 text-sm"
    aria-label="Click me to perform an action"
    role="button"
    tabindex="0"
    title="Perform an action">
    <slot />
  </button>
</template>

