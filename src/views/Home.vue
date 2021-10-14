<template>
  <div class="home">
    <div id="myID">Calendar</div>
  </div>
</template>

<style></style>

<script>
import flatpickr from "flatpickr";
export default {
  data: function () {
    return {};
  },
  mounted: function () {
    let calendar = flatpickr("#myID", { inlilne: true, enableTime: true, mode: "range", minDate: "2020-01" });
    calendar.currentMonth;
  },
  methods: {},
};
</script>
