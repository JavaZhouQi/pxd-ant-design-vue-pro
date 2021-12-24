<template>
  <global-footer class="footer custom-render">
    <template v-slot:links>
      <a href="https://www.github.com/vueComponent/pro-layout" target="_blank">Pro Layout Github</a>
      <a href="https://www.github.com/vueComponent/ant-design-vue-pro" target="_blank">ant-design-vue-pro Github</a>
      <a href="https://www.github.com/sendya/" target="_blank">@Sendya</a>
      <a href="https://www.github.com/javazhouqi/" target="_blank">@PiXiaoDan</a>
      <a href="https://github.com/vueComponent" target="_blank">vueComponent</a>
    </template>
  </global-footer>
</template>

<script>
import { GlobalFooter } from '@ant-design-vue/pro-layout'

export default {
  name: 'ProGlobalFooter',
  components: {
    GlobalFooter
  }
}
</script>
