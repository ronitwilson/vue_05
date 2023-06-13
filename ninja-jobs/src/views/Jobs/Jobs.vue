<template>
    <div >
      <h1>Jobs</h1>
      <div v-for="job in jobs" :key="job.id">
        <h2>{{ job.title }}</h2>
        <h2>{{ job.id }}</h2>
        <h2>{{ job.details }}</h2>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Jobs',
    components: {
    },
    data() {
        return {
            jobs: [
            { title: 'Ninja UX Designer', id: 1, details: 'lorem' },
            { title: 'Ninja Frontend', id: 2, details: 'lorem' },
            { title: 'Ninja Backend', id: 3, details: 'lorem' }
            ]
        }
    }

  }
  </script>

<style>

</style>
