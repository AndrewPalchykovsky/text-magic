<template>
  <div class="all-contacts-nav d-flex flex-wrap align-center justify-space-between mx-auto">
    <a href="" class="all-contacts-nav__item text-decoration-none">
        Open
      <i class="icon-badge">6</i>
      </a>

    <a href="" class="all-contacts-nav__item all-contacts-nav__item_active text-decoration-none">
        Timeline
    </a>
    <a href="" class="all-contacts-nav__item  text-decoration-none">
      Conversations
    </a>
    <a href="" class="all-contacts-nav__item text-decoration-none">
      Notes
    </a>
    <a href="" class="all-contacts-nav__item text-decoration-none">
      Tasks
    </a>
    <a href="" class="all-contacts-nav__item text-decoration-none">
      Deals
    </a>
    <a href="" class="all-contacts-nav__item text-decoration-none">
      Campaigns
    </a>
    <a href="" class="all-contacts-nav__item text-decoration-none">
      Feedback
    </a>
  </div>
</template>

<script>
export default {
name: "AllContactsNav"
}
</script>

<style lang="sass" scoped>
.all-contacts-nav
  padding: 20px 0
  max-width: 800px
  width: 100%
  &__item
    font-family: "HelveticaNeueMedium", Inter
    font-size: 14px
    font-weight: 500
    letter-spacing: 0
    line-height: 17px
    color: #5B6876
    padding: 4px 10px
    border: 1px solid transparent

    &_active
      padding: 4px 10px
      color: white
      border: 1px solid #005C88
      border-radius: 18px
      background-color: #005C88


.icon-badge
  height: 15px
  min-width: 17px
  line-height: 15px
  font-size: 12px
  border-radius: 18px
  background-color: #F7B500
  display: inline-block
  font-style: normal
  color: white






</style>
