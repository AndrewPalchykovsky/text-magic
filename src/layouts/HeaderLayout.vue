<template>
  <header class="header">
    <div class="d-flex align-center header-left">

      <v-btn
          icon
          tile
          class="menu-button">
        <v-icon class="menu-icon">mdi-menu</v-icon>
      </v-btn>

      <img src="../assets/logo.svg" alt="logo" class="logo">

      <v-btn tile
             depressed
             color="success"
             class="header-btn"
      >
        <v-icon left
                class="header-btn-plus">mdi-plus
        </v-icon>
        New
      </v-btn>

      <div class="header-search">
        <input type="search" class="header-search__input" placeholder="Search">
        <v-icon class="header-search__icon">mdi-magnify</v-icon>
      </div>

    </div>

    <div class="d-flex align-center">
      <v-btn
          dark
          small
          outlined
          class="status-button"
      >
        <v-icon class="status-icon status-icon_online">mdi-circle-medium</v-icon>
        Online
        <i class="arrow-down status-arrow_down"></i>
      </v-btn>

      <div class="header-icons">


        <v-badge
            color="#f66"
            overlap
            content="2"
            offset-x="18"
            offset-y="18"
            class="icon-notification-badge"
        >
          <v-btn depressed
                 text
                 icon
                 >
            <v-icon color="white" class="icon-notification">mdi-bell</v-icon>
          </v-btn>
        </v-badge>

        <v-btn depressed
               text
               icon
               rounded>
          <v-icon color="white" class="icon-settings">mdi-settings</v-icon>
        </v-btn>


      </div>

      <div class="d-flex align-center">
        <v-avatar size="28">
          <v-img src="https://cdn.vuetifyjs.com/images/john.png"></v-img>
        </v-avatar>
        <i class="arrow-down status-arrow_down"></i>
      </div>


    </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderLayout',
}
</script>

<style lang="sass" scoped>
.header
  display: flex
  position: fixed
  height: 50px
  left: 0
  right: 0
  top: 0
  padding: 11px 20px
  justify-content: space-between
  align-items: center
  z-index: 10000
  background: #005c89
  color: #fff
  &-left
    margin-left: -10px

.menu-icon
  color: white !important
  height: 18px !important
  width: 18px !important
  font-size: 20px !important

.logo
  width: 114px
  margin-top: -6px
  margin-bottom: -6px

  &:hover
    cursor: pointer

.header-btn.success
  height: 28px !important
  margin-left: 21px
  padding: 0 13px 1px 11px !important
  min-width: 36px
  border-radius: 4px
  font-size: 14px !important
  font-weight: bold !important
  text-transform: initial !important
  background-color: #69bc35 !important
  border-color: #69bc35 !important
  letter-spacing: 0.02em

.header-btn-plus
  font-size: 16px !important
  margin-right: 1px !important
  font-weight: bold !important
  margin-left: -1px!important

.header-search
  margin-left: 1rem !important
  height: 28px
  position: relative

  &__icon
    position: absolute !important
    top: calc(50% - 8px)
    left: 6px
    height: 16px
    width: 16px
    color: white !important
    opacity: 0.6
    font-size: 14px !important

  &__input
    border: none !important
    border-radius: 4px !important
    height: inherit
    padding-left: 29px
    width: 260px
    background-color: #03496D
    -webkit-appearance: none
    font-size: 12px
    color: white
    &::placeholder
      height: 14px
      width: 38px
      color: #9AB6C4
      font-size: 12px
      letter-spacing: 0.02em
      line-height: 14px
    &:focus
      background-color: white
      outline: 0
      color: #3b4857

      & + .header-search__icon
        color: #3b4857 !important

.status-button
  position: relative
  font-size: 12px
  text-transform: initial
  font-weight: bold
  font-family: "Helvetica Neue"
  letter-spacing: 0
  line-height: 15px
  width: 88px
  height: 28px !important
  text-align: left
  padding: 0 10px !important

  .status-icon
    margin-top: 0
    margin-left: -5px !important
    margin-right: 3px !important
    width: 16px !important
    height: 16px !important

    &_online
      color: #69BC35 !important


.status-arrow_down
  margin-left: 7px
  margin-top: 2px

.header-icons
  margin: 0 10px 0 5px

.icon-notification
  font-size: 18px !important

.icon-settings
  font-size: 18px !important

.menu-button
  min-height: 40px
  min-width: 40px
  width: 40px!important
  height: 40px!important



</style>
