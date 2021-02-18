<template>
  <v-timeline-item class="timeline-item" icon-color="#8392A5" fill-dot icon="mdi-chat" color="white">
    <div class="card text-left">
      <div class="d-flex justify-space-between">
        <h3 class="card__header d-inline-block">
          Chat started: Hello, anybody here?
        </h3>
        <small class="card__time">
          20 Dec 8:13 am
        </small>
      </div>
      <div class="card__text mt-3 mb-0">

        <span class="mr-5">
          <span class="card__text_secondary">Chat ID: </span><span class="highlighted">784732</span>
        </span>

        <span class="mr-5">
          <span class="card__text_secondary">From: </span><a href="mailto:kshlerin.kaleb@feest.com" class="highlighted text-decoration-none">kshlerin.kaleb@feest.com</a>
        </span>

        <span class="mr-5">
          <span class="card__text_secondary mr-1">Assignee: </span>
          <v-avatar size="20" class="mr-1">
            <v-img src="https://cdn.vuetifyjs.com/images/john.png"></v-img>
          </v-avatar>
          Adrian Baker
        </span>

      </div>
    </div>
  </v-timeline-item>
</template>

<script>
export default {
name: "ChatTimeline"
}
</script>

<style scoped>

</style>
