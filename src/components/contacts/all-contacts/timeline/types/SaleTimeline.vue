<template>
  <v-timeline-item class="timeline-item" icon-color="#8392A5" fill-dot icon="mdi-sale" color="white">
    <div class="card text-left">
      <div class="d-flex justify-space-between">
        <h3 class="card__header d-inline-block">
          Campaign sent: Summer Sale 50% Off
        </h3>
        <small class="card__time">
          4 Feb 5:36 am
        </small>
      </div>
      <div class="card__text mt-3 mb-0">

        <span class="mr-5">
          <span class="card__text_secondary">From: </span>
          <a href="mailto:newsletter@textmagic.com" class="highlighted text-decoration-none">newsletter@textmagic.com</a>
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">To: </span>
          488 recipients
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">Opened: </span>
          Yes
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">Clicked: </span>
          Yes
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">Unsubscribed: </span>
          No
        </span>

      </div>
    </div>
  </v-timeline-item>
</template>

<script>
export default {
name: "SaleTimeline"
}
</script>

<style scoped>

</style>
