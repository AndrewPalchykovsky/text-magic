<template>
  <main class="content">
    <AllContacts></AllContacts>
  </main>
</template>


<script>

import AllContacts from '../components/contacts/all-contacts/AllContacts.vue'


export default {
  name: "ContentLayout",
  components: {
    AllContacts
  }
}
</script>

<style lang="sass" scoped>
.content
  padding-left: 200px

</style>
