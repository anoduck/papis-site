<template>
  <div class="papis-content">
    <LeftMenu/>
    <PapersList/>
    <PaperDetail/>
    <BottomRightButtons/>
  </div>
</template>

<script>

import LeftMenu from './LeftMenu.vue'
import PapersList from './PapersList.vue'
import PaperDetail from './PaperDetail.vue'
import BottomRightButtons from './BottomRightButtons.vue'


export default {
  name: 'Content',
  components: {
    LeftMenu,
    PapersList,
    PaperDetail,
    BottomRightButtons
  }
}
</script>
