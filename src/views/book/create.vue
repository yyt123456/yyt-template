<template>
  <div>
    <div>{{styles.menuText}}</div>
    <div class="blue">
      123
    </div>
  </div>
</template>
<script>
  import styles from '../../styles/variables.scss'

  export default {
    computed: {
      styles() {
        return styles
      }
    }
  }
</script>
<style lang="scss" scoped>
  @import "../../styles/variables";

  .blue {
    color: $menuActiveText;
  }
</style>