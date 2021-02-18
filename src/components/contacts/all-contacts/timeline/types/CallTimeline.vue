<template>
  <v-timeline-item class="timeline-item" icon-color="#8392A5" fill-dot icon="mdi-phone" color="white">
    <div class="card text-left">
      <div class="d-flex justify-space-between">
        <h3 class="card__header d-inline-block">
          Incoming call (2:43)
        </h3>
        <small class="card__time">
          28 Sep 6:06 am
          <v-icon class="icon-pin">mdi-pin</v-icon>
        </small>
      </div>
      <div class="card__text d-flex pt-3 mb-0">
        <span class="mr-5">
         <span class="card__text_secondary">From: </span><a href="tel:6628827462" class="highlighted text-decoration-none">(662) 882-7462</a>
        </span>

        <span class="mr-5">
         <span class="card__text_secondary">Chat ID: </span><span class="highlighted">882732</span>
        </span>

        <span class="mr-5">
         <span class="card__text_secondary">To: </span><a href="tel:2344365678" class="highlighted text-decoration-none">(234) 346-5678</a>
        </span>

        <span class="d-flex mr-5">
         <span class="card__text_secondary">Recording: </span>

          <span class="ml-1 audioplayer">

            <span class="audioplayer-toogle mr-1">
              <v-btn
                  depressed
                  icon
                  x-small
                  class="audioplayer__button"
              >
                <v-icon color="#005C8A" class="audioplayer-icon audioplayer-icon-play">mdi-play</v-icon>
                <v-icon color="#005C8A" class="audioplayer-icon audioplayer-icon-pause">mdi-pause</v-icon>
              </v-btn>
            </span>
            <v-progress-linear v-model="time" height="2" class="audioplayer__progress" value="15"></v-progress-linear>
             <span class="audioplayer__time">{{time}}</span>
          </span>

        </span>


      </div>
    </div>
  </v-timeline-item>
</template>

<script>
export default {
  name: "CallTimeline",
  data: () => ({
    time: '2:34',

  }),
}
</script>

<style lang="sass" scoped>
.audioplayer
  margin-top: -3px


</style>
