<template>
  <div class="sidebar d-flex flex-column">
    <nav>
      <ul>
        <li class="nav-list-item">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-view-dashboard</v-icon>
            Dashboard
          </a>
        </li>

        <li class="nav-list-item">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-message</v-icon>
            Messaging
            <v-icon color="#5c6876" class="nav-list-item__link-icon-expand">mdi-menu-down</v-icon>
          </a>
        </li>

        <li class="nav-list-item">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-account-supervisor</v-icon>
            Contacts
            <v-icon color="#5c6876" class="nav-list-item__link-icon-expand">mdi-menu-down</v-icon>
          </a>
        </li>
        <div class="list-group">
          <ul>
            <li class="list-group-item active">
              <a href="" class="list-group-item__link">All contacts</a>
            </li>
            <li class="list-group-item ">
              <a href="" class="list-group-item__link">Lists</a>
            </li>
            <li class="list-group-item ">
              <a href="" class="list-group-item__link">Segments</a>
            </li>
            <li class="list-group-item ">
              <a href="" class="list-group-item__link">Organizations</a>
            </li>
            <li class="list-group-item ">
              <a href="" class="list-group-item__link">Imports</a>
            </li>
            <li class="list-group-item ">
              <a href="" class="list-group-item__link">Unsubscribers</a>
            </li>
          </ul>

        </div>

        <li class="nav-list-item">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-briefcase-check</v-icon>
            Tasks
          </a>
        </li>

        <li class="nav-list-item">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-handshake</v-icon>
            Deals
          </a>
        </li>

        <li class="nav-list-item">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-calendar</v-icon>
            Calendar
          </a>
        </li>

        <li class="nav-list-item">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-settings</v-icon>
            Services
          </a>
        </li>

        <li class="nav-list-item">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-file-check</v-icon>
            Reporting
          </a>
        </li>

        <li class="nav-list-item nav-list-item_last">
          <a href="" class="nav-list-item__link">
            <v-icon color="#5c6876" class="nav-list-item__link-icon-prepend">mdi-help-circle</v-icon>
            Help
          </a>
        </li>

      </ul>
    </nav>

  </div>
</template>

<script>
export default {
  name: 'SidebarLayout',
}
</script>

<style lang="sass" scoped>

.sidebar
  width: 200px
  position: fixed
  top: 50px
  left: 0
  bottom: 0
  background: #f9fafc
  padding: 10px 0
  &:after
    content: ""
    position: absolute
    right: 0
    top: 0
    bottom: 0
    width: 1px
    background: #e5e9f2
    z-index: 1
  ul
    list-style-type: none
    padding-left: 0
    .nav-list-item
      height: 42px
      display: flex
      justify-content: center
      align-items: center
      position: relative
      &_last
        bottom: 0
        width: 100%
        position: absolute

      &:hover
        .nav-list-item__link
          border-radius: 5px
          background-color: #e5e9f2

      .nav-list-item__link
        text-decoration: none
        color: #5C6876
        font-size: 16px
        font-weight: 500
        font-family: "HelveticaNeueMedium", Inter,sans-serif
        letter-spacing: 0
        line-height: 20px
        width: 90%
        padding: 8px 12px
        display: flex
        align-items: center
        &-icon-prepend
          margin-right: 10px
        &-icon-expand
          position: absolute
          right: 15px
          top: calc(50% - 11px)
          font-size: 20px

      &.nav-list-item_active
        color: #005C88

.list-group
  &-item
    text-align: left
    &:hover
      .list-group-item__link
        position: relative
        width: 100%
        &:before
          content: ''
          position: absolute
          border-radius: 5px
          background-color: #e5e9f2
          z-index: -1
          top: 2px
          bottom: 2px
          right: 62px
          left: -52px
    &.active
      box-shadow: inset 3px 0 0 0 #005C88
      border-top: 1px solid #E5E9F2
      border-bottom: 1px solid #E5E9F2
      border-right: 1px solid white
      background-color: white
      position: relative
      &:after
        content: ""
        position: absolute
        top: 1px
        bottom: 1px
        right: -1px
        width: 1px
        background: #fff
        z-index: 2
      .list-group-item__link
        color: #005C88
    &__link
      display: inline-block
      height: 33px
      line-height: 33px
      text-decoration: none
      color: #5C6876
      margin-left: 57px
      font-size: 14px



</style>
