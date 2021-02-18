<template>
  <section class="all-contacts">
    <AllContactsHeader></AllContactsHeader>
    <div class="d-flex">
      <AllContactsDetails></AllContactsDetails>
      <div class="d-flex flex-column content-holder">
        <AllContactsNav></AllContactsNav>
        <TimelineHeader></TimelineHeader>
        <TimelineContent></TimelineContent>
      </div>
    </div>
  </section>
</template>

<script>

import AllContactsHeader from "./AllContactsHeader";
import AllContactsDetails from "./AllContactsDetails";
import AllContactsNav from "./AllContactsNav";
import TimelineHeader from "./timeline/TimelineHeader";
import TimelineContent from "./timeline/TimelineContent";

export default {
name: "AllContacts",
  components: {
    AllContactsHeader,
    AllContactsDetails,
    AllContactsNav,
    TimelineHeader,
    TimelineContent
  }
}
</script>

<style lang="sass" scoped>
.content-holder
  width: 100%
  max-width: calc(100% - 300px)
  background-color: #F5FAFF


</style>
