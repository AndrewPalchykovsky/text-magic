<template>
  <v-timeline-item class="timeline-item" icon-color="#8392A5" fill-dot icon="mdi-account" color="white">
    <div class="card text-left">
      <div class="d-flex justify-space-between">
        <h3 class="card__header d-inline-block">
          Contact created
        </h3>
        <small class="card__time">
          8 Apr 3:58 am
        </small>
      </div>
      <div class="card__text mt-3 mb-0">

        <span class="mr-5">
          <span class="card__text_secondary mr-1">Agent: </span>
          <v-avatar size="20" class="mr-1">
            <v-img src="https://cdn.vuetifyjs.com/images/john.png"></v-img>
          </v-avatar>
          Ray Bennett
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">Source: </span> Import (Customers Apr 2020)
        </span>

      </div>
    </div>
  </v-timeline-item>
</template>

<script>
export default {
name: "ContactTimeline"
}
</script>

<style scoped>

</style>
