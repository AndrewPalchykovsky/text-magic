<template>
  <section class="contact-details">

    <div class="search mb-4">
      <input type="search" placeholder="Search contact properties" class="search__input">
      <v-icon class="search__icon">mdi-magnify</v-icon>
    </div>

    <div class="contact-details-info d-flex flex-column align-start">
      <h3 class="contact-details-info__header">Email</h3>
      <a class="contact-details-info__content_link text-decoration-none mt-1" href="mailto:andrewlinkoln@textmagic.com">andrewlinkoln@textmagic.com</a>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Phone</h3>
      <a class="contact-details-info__content_link text-decoration-none mt-1" href="tel:9903389983">(990) 338-9983 <span class="secondary-info">(Work)</span></a>
      <a class="contact-details-info__content_link text-decoration-none mt-1" href="tel:9903389983">(990) 998-2246 <span class="secondary-info">(Mobile)</span></a>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Contact owner</h3>
      <p class="contact-details-info__content contact-owner d-flex align-center mt-2">
        <v-avatar size="25" class="mr-2">
          <v-img src="https://cdn.vuetifyjs.com/images/john.png"></v-img>
        </v-avatar>
        Robert Overit <v-icon class="contact-owner-icon">mdi-menu-down</v-icon></p>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Position</h3>
      <p class="contact-details-info__content mt-1">Manager</p>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Department</h3>
      <p class="contact-details-info__content mt-1">Sales</p>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Birthday</h3>
      <p class="contact-details-info__content mt-1">24 May 1989</p>
    </div>

    <div class="contact-details-info  d-flex align-start mt-2">
      <a class="contact-details-info__content_link">Show 12 more</a>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Lists</h3>
      <div class="d-flex flex-wrap">
        <div class="chip mt-1 mr-2">
          Sales
          <v-icon class="chip-icon ml-1">mdi-close</v-icon>
        </div>

        <div class="chip mt-1 mr-2">
          United States
          <v-icon class="chip-icon ml-1">mdi-close</v-icon>
        </div>

        <div class="chip mt-1 mr-2">
          United Kingdom
          <v-icon class="chip-icon ml-1">mdi-close</v-icon>
        </div>

        <div class="chip mt-1 mr-2">
          France
          <v-icon class="chip-icon ml-1">mdi-close</v-icon>
        </div>
      </div>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Segments</h3>
      <div class="d-flex flex-wrap">
        <div class="chip mt-1 mr-2">
          My custom segment
        </div>
      </div>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Attachments</h3>
      <div class="d-flex flex-column">
        <div class="file-wrapper d-flex align-center mt-1">
          <div class="file mr-2">
            <v-icon class="file-icon">mdi-attachment</v-icon>
          </div>
          <p class="contact-details-info__content ">Documents.pdf <span class="secondary-info">1.7 mb</span></p>
        </div>
        <div class="file-wrapper d-flex align-center mt-1">
          <div class="file mr-2">
            <v-icon class="file-icon">mdi-attachment</v-icon>
          </div>
          <p class="contact-details-info__content ">My-archive.zip <span class="secondary-info">230 kb</span></p>
        </div>
      </div>
    </div>

    <div class="contact-details-info d-flex flex-column align-start mt-4">
      <h3 class="contact-details-info__header">Tags</h3>
      <div class="d-flex flex-wrap">
        <div class="tag mt-1 mr-2">
          account
          <v-icon class="chip-icon ml-1">mdi-close</v-icon>
        </div>

        <div class="tag mt-1 mr-2">
         issue
          <v-icon class="chip-icon ml-1">mdi-close</v-icon>
        </div>

        <div class="tag mt-1 mr-2">
          tags
          <v-icon class="chip-icon ml-1">mdi-close</v-icon>
        </div>


      </div>
    </div>



  </section>
</template>

<script>
export default {
name: "AllContactsDetails"
}
</script>

<style lang="sass" scoped>
.contact-details
  padding: 20px
  width: 300px
  background-color: #fff
  box-shadow: -1px 0 0 0 #E5E9F2, 1px 0 0 0 #E5E9F2
  margin-top: 1px
  box-sizing: border-box
  height: calc(100vh - 50px - 76px)
  overflow-y: auto

.contact-details-info
  &__header
    color: #8392A5
    font-size: 14px
    font-weight: 500
    font-family: "HelveticaNeueMedium", Inter,sans-serif
    letter-spacing: 0
    line-height: 17px
  &__content
    margin-bottom: 0
    @extend .contact-details-info__header
    color: #3B4857
    &_link
      @extend .contact-details-info__header
      color: #005C88

.secondary-info
  color: #8392A5
  font-weight: 500
  font-family: "HelveticaNeueMedium", Inter,sans-serif

.chip
  color: #005C88
  height: 20px
  line-height: 20px
  border-radius: 14px
  border: 1px solid #CCD4E6
  display: flex
  align-items: center
  font-size: 12px
  font-weight: bold
  padding: 2px 8px 3px
.chip-icon
  font-size: 12px!important
  color: #8392A5
  margin-bottom: -2px
 
.file
  background-color: #E5E9F2
  height: 28px
  width: 28px
  border-radius: 4px
  &-icon
    transform: rotate(45deg)
    font-size: 16px!important
    color: #005C88!important
  &-wrapper
    &:hover
      cursor: pointer

.tag
  color: #005C88
  height: 22px
  line-height: 22px
  border-radius: 4px
  display: flex
  align-items: center
  font-size: 12px
  padding: 2px 8px 3px
  background-color: #E5E9F2
  font-weight: 500
  font-family: "HelveticaNeueMedium", Inter,sans-serif

.contact-owner
  &:hover
    cursor: pointer

.contact-owner-icon
  font-size: 16px!important
  color: #5B6876!important
  margin-top: -2px!important


</style>
