<template>
  <div class="main-layout">
    <HeaderLayout></HeaderLayout>
    <SidebarLayout></SidebarLayout>
    <ContentLayout></ContentLayout>
  </div>
</template>


<script>
import HeaderLayout from './HeaderLayout.vue'
import SidebarLayout from './SidebarLayout.vue'
import ContentLayout from './ContentLayout.vue'

export default {
  name: 'MainLayout',
  components: {
    HeaderLayout,
    SidebarLayout,
    ContentLayout
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>

.main-layout
  padding-top: 50px
  height: 100%

</style>
