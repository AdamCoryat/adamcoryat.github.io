<template>
  <nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-transparent">
    <div>
      <h1 class="mx-2 text-light">Adam Coryat</h1>
    </div>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div
      class="d-flex justify-content-end collapse navbar-collapse"
      id="navbarText"
    >
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a href="#landing-about" v-smooth-scroll
            ><h4 class="mx-2 text-light">About Me</h4></a
          >
        </li>
        <li class="nav-item">
          <a href="#landing-skills" v-smooth-scroll
            ><h4 class="mx-2 text-light">Skills</h4></a
          >
        </li>
        <li class="nav-item">
          <a href="#landing-applications"
            ><h4 class="mx-2 text-light" v-smooth-scroll>Applications</h4></a
          >
        </li>
        <li class="nav-item">
          <a href="#landing-contact" v-smooth-scroll
            ><h4 class="mx-2 text-light">Contact</h4></a
          >
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
import { getUserData } from "@bcwdev/auth0-vue";
import { setBearer, resetBearer } from "../services/AxiosService";
export default {
  name: "Navbar",
  methods: {
    async login() {
      await this.$auth.loginWithPopup();
      if (this.$auth.isAuthenticated) {
        setBearer(this.$auth.bearer);
        this.$store.dispatch("getProfile");
        // NOTE if you want to do something everytime the user logs in, do so here
      }
    },
    async logout() {
      resetBearer();
      await this.$auth.logout({ returnTo: window.location.origin });
    },
  },
};
</script>

<style></style>
