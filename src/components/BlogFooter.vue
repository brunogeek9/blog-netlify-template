<template>
  <transition appear name="v--mask">
    <footer v-once class="blog__footer">
      <div class="signature cosmicjs">
        Proudly powered by <a href="https://www.linkedin.com/in/brunojamelli/" target="_blank">Bruno Jamelli</a>
      </div>
    </footer>
  </transition>
</template>

<script>
export default { name: 'blog-footer' }
</script>
