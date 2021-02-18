<template>
  <div class="contacts-header d-flex justify-space-between">
    <div class=" d-flex">
      <v-btn icon
             class="contacts-header__icon-back">
        <v-icon>mdi-chevron-left</v-icon>
      </v-btn>
      <div class="d-flex align-center">
        <v-avatar size="40">
          <v-img src="https://cdn.vuetifyjs.com/images/john.png"></v-img>
        </v-avatar>
        <div class="d-flex flex-column align-start contacts-header-info">
          <h2 class="contacts-header-info__text">Ruth Adkins</h2>
          <small class="d-flex flex-wrap align-center contacts-header-info__text-small">
            <v-icon class="contacts-header-info__icon contacts-header-info__icon-marker">mdi-map-marker</v-icon>
            United States
            <v-icon class="contacts-header-info__icon contacts-header-info__icon-outline">mdi-clock-outline</v-icon>
            4:24 pm (UTC -4)
            <v-icon class="contacts-header-info__icon contacts-header-info__icon-building">mdi-office-building</v-icon>
            TextMagic
          </small>
        </div>
      </div>
    </div>
    <div class="d-flex align-center">
      <v-btn  tile
              depressed
              outlined
              color="success"
              class="btn btn-round mr-2">
        <v-icon class="icon-plus">mdi-plus</v-icon>
        New
      </v-btn>

      <v-btn  tile
              depressed
              outlined
              class="btn btn-round mr-2">
        <v-icon class="btn_with-icon mr-1">mdi-phone</v-icon>
        Call
      </v-btn>

      <v-btn  tile
              depressed
              outlined
              class="btn btn-round mr-2">
        <v-icon class="btn_with-icon mr-1">mdi-file</v-icon>
        Add note
      </v-btn>

      <v-btn  tile
              depressed
              outlined
              class="btn btn-round mr-2">
        <v-icon class="icon-attach mr-1">mdi-attachment</v-icon>
        Attach file
      </v-btn>

      <v-btn  tile
              depressed
              outlined
              class="btn btn-round mr-2">
        <v-icon class="btn_with-icon mr-1">mdi-pencil</v-icon>
        Edit
      </v-btn>

      <v-btn  tile
              depressed
              outlined
              class="btn btn-round">
        <v-icon class="icon-dots mr-1">mdi-dots-vertical</v-icon>
        More
      </v-btn>

    </div>
  </div>
</template>

<script>
export default {
  name: "AllContactsHeader"
}
</script>

<style lang="sass" scoped>
  .contacts-header
    padding: 16px 20px
    background-color: white
    box-shadow: 0 1px 0 0 #E5E9F2, -1px 0 0 0 #E5E9F2
    &__icon-back
      padding: 6px
      border: 1px solid #D4DAE1
      border-radius: 4px
      background-color: #F9FAFC
      height: 33px
      width: 33px
      margin-right: 12px
    &-info
      margin-left: 12px
      &__icon
        font-size: 12px!important
        color: #8392A5!important
        &-marker
          margin-right: 4px
        &-outline, &-building
          margin: 0 4px 0 12px
      &__text
        color: #3B4857
        font-size: 20px
        font-weight: 500
        font-family: "HelveticaNeueMedium", Inter,sans-serif
        letter-spacing: 0
        line-height: 25px
      &__text-small
        font-size: 12px
        color: #8392A5
.btn-round
  border: 1px solid #D4DAE1
  border-radius: 4px
  background-color: #F9FAFC
  text-transform: initial
  font-weight: bold
  height: 33px !important
  padding: 0 13px 1px 11px !important
  min-width: 36px
  font-size: 14px !important
  letter-spacing: 0.02em
  color: #5C6876!important
  .icon-plus
    font-size: 16px !important
    margin-right: 1px !important
    font-weight: bold !important
    margin-left: -1px!important
  .btn_with-icon
    font-size: 14px !important

.icon-attach
  transform: rotate(45deg)
  font-size: 15px!important

.icon-dots
  font-size: 16px!important
</style>
