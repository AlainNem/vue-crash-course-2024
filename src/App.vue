<script setup>
import NavBar from './components/NavBar.vue';
import Hero from './components/Hero.vue';
import HomeCards from './components/HomeCards.vue';
import JobsListings from './components/JobsListings.vue';
</script>

<template>
  <NavBar></NavBar>
  <Hero title="Vue js application" subtitle="First VueJs application"></Hero>
  <HomeCards/>
  <JobsListings :limit="3" :showButton=true />
</template>