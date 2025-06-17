<template>
  <div class="bottom-btn">
      <!-- add button BEGIN -->

      <a class="btn-floating btn-large">hover</a>
      <ul>
        <li><a class="btn-floating">1</a></li>
        <li><a class="btn-floating">2</a></li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'BottomRightButtons',
  data() {
    return {
      fab: fixedactionbutton
    }
  }
};
</script>
<style scoped>
.bottom-btn {
    bottom: 20px;
    right: 20px;
}
</style>
