<template>
  <div class="arrow-btn-block">
    {{title}}
    <svg
      width="54"
      height="28"
      viewBox="0 0 54 28"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M42.4762 14.3095H1M42.4762 14.3095L40 12.1429M42.4762 14.3095L40 16.4762M53 14C53 21.1797 47.1797 27 40 27C32.8203 27 27 21.1797 27 14C27 6.8203 32.8203 1 40 1C47.1797 1 53 6.8203 53 14Z"
        stroke="black"
        stroke-linecap="round"
        stroke-linejoin="round"
      />
    </svg>
  </div>
</template>

<script>
export default {
  props:['title']
};
</script>

<style>
</style>