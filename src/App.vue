<!-- src/App.vue -->
<template>
  <div id="app">
    <EmployeeList />
  </div>
</template>

<script>
import EmployeeList from './components/EmployeeList.vue';

export default {
  components: {
    EmployeeList
  }
};
</script>
<style>
body{
  background: gainsboro;
}
#app{
  display: flex;
  justify-content: center;
}
</style>
