<template>
  <div id="app">
    {{ msg }}

    <p>{{ message }}</p>
    <input v-model="message" />
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data: () => ({
    message: "Hello World!",
    visibility: true,
    items: [
      { id: 1, text: "アイテム1" },
      { id: 2, text: "アイテム2" },
      { id: 3, text: "アイテム3" },
    ],
  }),
  methods: {
    clickedEvent() {
      console.log("clicked!");
    },
  },
};
</script>
