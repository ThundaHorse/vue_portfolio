<template>
  <div id="app">
    <div id="nav">
      <Navbar></Navbar>
    </div>
    <router-view />
  </div>
</template>

<script>
import Navbar from "../src/components/Navbar";

export default {
  name: "app",
  components: {
    Navbar
  },
  data: function() {
    return {};
  },
  created: function() {},
  methods: {}
};
</script>
