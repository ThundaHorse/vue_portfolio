<template>
  <div class="navBar">
    <nav class="navbar navbar-dark bg-dark navbar-expand-lg">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <img src="../assets/abe_headshot.png" alt="headshot" id="headshot" />
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <router-link class="nav-link" to="/">
              Home
              <span class="sr-only">(current)</span>
            </router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/about">About Me</router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="https://github.com/ThundaHorse">Github</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="https://medium.com/@abekeeem">Medium</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<style scoped>
div.collapse {
  justify-content: center;
  margin-top: 200px;
}
#headshot {
  width: auto;
  height: 150px;
  border-radius: 50%;
  position: relative;
  left: 50%;
  margin-left: -50px !important;
  display: block;
}
</style>

<script>
export default {
  name: "Navbar",
  data: function() {
    return {};
  },
  created: function() {},
  methods: {}
};
</script>
