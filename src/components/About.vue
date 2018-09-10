<template>
  <div class="about">
<h1>About, hey {{ their_name }} </h1>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
     return {
       their_name: this.$route.params.name
     }
    },
    }

</script>