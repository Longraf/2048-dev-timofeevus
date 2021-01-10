<template>
    <Default />

</template>

<script>
  import Default from "./components/Default";

  export default {
    name: 'App',
    components: {
      Default
    }
  }
</script>

<style lang="scss">

  #nav {
    padding: 30px;
    background-color: greenyellow;


    a{
      font-weight: bold;
      color: #2c3e50;
    }

    a.router-link-exact-active {
      color: #42b983;
    }
  }

</style>
