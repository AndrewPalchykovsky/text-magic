<template>
  <div class="d-flex justify-space-between timeline-header">
    <h1 class="timeline-header__text d-inline-block">Timeline</h1>
    <div class="timeline-header-controls d-flex align-center">

        <v-btn tile
               depressed
               outlined
               class="btn btn-round mr-2">
          <v-icon class="btn_with-icon btn_filter mr-1">mdi-filter-menu</v-icon>
          Filters
        </v-btn>

      <v-btn tile
             depressed
             outlined
             class="btn btn-round mr-2">
        <v-icon class="btn_with-icon btn_filter mr-1">mdi-arrow-expand-vertical</v-icon>
        Expand all
      </v-btn>

      <div class="search">
        <input type="search" placeholder="Search contact properties" class="search__input search__input_small">
        <v-icon class="search__icon">mdi-magnify</v-icon>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: "AllContactsTimelineHeader"
}
</script>

<style lang="sass" scoped>
.timeline-header
  width: 100%
  padding: 0 20px 20px
  &__text
    font-family: "HelveticaNeueMedium", Inter, sans-serif
    font-size: 20px
    font-weight: 500
    letter-spacing: 0
    line-height: 33px

.btn-round
  border: 1px solid #D4DAE1
  border-radius: 4px
  background-color: #F9FAFC
  text-transform: initial
  font-family: "HelveticaNeueMedium", Inter, sans-serif
  font-weight: 500
  height: 28px !important
  padding: 0 13px 1px 11px !important
  min-width: 36px
  font-size: 12px !important
  letter-spacing: 0.02em
  color: #5C6876!important
  .btn_with-icon
    font-size: 13px !important
    color: #8392A5!important
  .btn_filter
    margin-bottom: -2px


</style>
