<template>
    <div class="timeline-content ">
      <v-timeline
          align-top
          dense
          class="mr-5 pa-0"
      >

        <NoteTimeline></NoteTimeline>
        <TicketTimeline></TicketTimeline>
        <CallTimeline></CallTimeline>
        <ChatTimeline></ChatTimeline>
        <SaleTimeline></SaleTimeline>
        <FeedbackTimeline></FeedbackTimeline>
        <DealTimeline></DealTimeline>
        <ContactTimeline></ContactTimeline>
      </v-timeline>
    </div>
</template>

<script>

import NoteTimeline from './types/NoteTimeline'
import TicketTimeline from './types/TicketTimeline'
import CallTimeline from './types/CallTimeline'
import ChatTimeline from './types/ChatTimeline'
import SaleTimeline from './types/SaleTimeline'
import FeedbackTimeline from './types/FeedbackTimeline'
import DealTimeline from './types/DealTimeline'
import ContactTimeline from './types/ContactTimeline'

export default {
  name: "AllContactTimelineContent",
  components: {
    NoteTimeline,
    TicketTimeline,
    CallTimeline,
    ChatTimeline,
    SaleTimeline,
    FeedbackTimeline,
    DealTimeline,
    ContactTimeline
  },
}
</script>

<style lang="sass" scoped>
.timeline-content
  overflow: auto
  scroll-behavior: smooth
  height: calc(100vh - 50px - 75px - 67px - 53px)

</style>
