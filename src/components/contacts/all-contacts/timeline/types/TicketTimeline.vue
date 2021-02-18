<template>
  <v-timeline-item class="timeline-item" icon-color="#8392A5" fill-dot icon="mdi-ticket" color="white">
    <div class="card text-left">
      <div class="d-flex justify-space-between">
        <h3 class="card__header d-inline-block">
          Ticket updated: My compose screen is not working!
        </h3>
        <small class="card__time">
          24 Dec 2:44 am
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
         <span class="card__text_secondary mr-1">Assignee: </span>
          <v-avatar size="20" class="mr-1">
            <v-img src="https://cdn.vuetifyjs.com/images/john.png"></v-img>
          </v-avatar>
          Ray Bennett
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">Status: </span>
          Open
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">Priority: </span>
          Normal
        </span>

      </div>
    </div>
  </v-timeline-item>
</template>

<script>
export default {
name: "TicketTimeline"
}
</script>

<style scoped>

</style>
