<template>
  <div>
      <router-link to="/map" class="router-link">Map</router-link>
      <hr>
      <TaskList />
  </div>
</template>

<script>
import TaskList from '@/components/TaskList'
export default {
  name: 'App',
  components: {
    TaskList
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
