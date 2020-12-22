<template>
  <div>
    <router-link to="/" class="router-link">Task</router-link>
    <hr>
    <MapList />
  </div>
</template>

<script>
import MapList from '@/components/MapList'
export default {
  name: 'App',
  components: {
    MapList
  }
}
</script>

<style>
.router-link {
  text-decoration: none;
  color: #2c3e50;
}
.router-link:hover {
  text-decoration: underline;
}
</style>
