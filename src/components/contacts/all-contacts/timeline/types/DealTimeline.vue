<template>
  <v-timeline-item class="timeline-item" icon-color="#8392A5" fill-dot icon="mdi-handshake" color="white">
    <div class="card text-left">
      <div class="d-flex justify-space-between">
        <h3 class="card__header d-inline-block">
          Deal updated: New annual offering
        </h3>
        <small class="card__time">
          15 Aug 8:41 am
        </small>
      </div>
      <div class="card__text mt-3 mb-0">

        <span class="mr-5">
          <span class="card__text_secondary mr-1">Assignee: </span>
          <v-avatar size="20" class="mr-1">
            <v-img src="https://cdn.vuetifyjs.com/images/john.png"></v-img>
          </v-avatar>
          Ray Bennett
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">Value: </span>$20,000
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">From: </span>
          <a href="mailto:kshlerin.kaleb@feest.com" class="highlighted text-decoration-none">kshlerin.kaleb@feest.com</a>
        </span>

      </div>
    </div>
  </v-timeline-item>
</template>

<script>
export default {
  name: "DealTimeline"
}
</script>

<style scoped>

</style>
