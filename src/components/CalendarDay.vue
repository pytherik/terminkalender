<script>
import CalendarEvent from "@/components/CalendarEvent.vue";

export default {
  name: "CalendarDay",
  components: {CalendarEvent},
}
</script>

<template>
  <div class="card">
    <div id="calendar-day">
      <div class="card-header text-center" role="button">
        <strong>Montag</strong>
      </div>
      <div class="card-body">
        <CalendarEvent/>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>