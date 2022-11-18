<template>
  <div>
    <h1>Calendar</h1>
    <p>events:</p>
    <p>{{ events }}</p>
    <button type="submit">fetch Events</button>
  </div>
</template>

<script>
export default {
  name: "CustomCalendar",
  data: () => ({
    events: [],
  }),
};
</script>
