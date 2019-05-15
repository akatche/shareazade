<template>
  <div id="app">
    <router-view/>
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          Creado por Alejandro Katcheroff @{{currentYear}}
        </p>
      </div>
    </footer>
  </div>
</template>

<style scoped>
  .footer{
    padding-top:2rem;
    padding-bottom:2rem;
  }
</style>

<script>
export default {
  name: 'app',
  computed: {
    currentYear: function () {
      let currentDate = new Date() ;
      return currentDate.getFullYear();
    }
  }
}
</script>
