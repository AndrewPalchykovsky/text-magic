<template>
  <v-timeline-item class="timeline-item" icon-color="#8392A5" fill-dot icon="mdi-thumb-up" color="white">
    <div class="card text-left">
      <div class="d-flex justify-space-between">
        <h3 class="card__header d-inline-block">
          Feedback received
        </h3>
        <small class="card__time">
          8 Apr 3:58 am
        </small>
      </div>
      <div class="card__text mt-3 mb-0">

        <span class="mr-5">
          <span class="card__text_secondary">Ticket ID: </span>
          <span class="highlighted">784732</span>
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">From: </span>
          <a href="mailto:kshlerin.kaleb@feest.com" class="highlighted text-decoration-none">kshlerin.kaleb@feest.com</a>
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">Comment: </span>
          Nice support, thank you guys!
        </span>

      </div>
    </div>
  </v-timeline-item>
</template>

<script>
export default {
  name: "FeedbackTimeline"
}
</script>

<style scoped>

</style>
