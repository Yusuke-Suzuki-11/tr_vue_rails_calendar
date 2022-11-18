<template>
  <CustomCalendar />
</template>

<script>
import CustomCalendar from "./components/CustomCalendar.vue";

export default {
  name: "App",
  components: {
    CustomCalendar,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
