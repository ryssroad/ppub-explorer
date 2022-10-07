<template>
  <p class="clearfix mb-0">
    <span class="float-md-center d-none d-md-block d-md-inline-block mt-25">
      modified by
      <b-link
        class="ml-25 font-weight-bolder"
        href="#"
        target="_blank"
      >ryssroad#7010</b-link>
    </span>
  </p>
</template>

<script>
import { BLink, VBPopover } from 'bootstrap-vue'
import Ripple from 'vue-ripple-directive'

export default {
  name: 'AppFooter',
  components: {
    BLink,
  },
  directives: {
    'b-popover': VBPopover,
    Ripple,
  },
}
</script>
