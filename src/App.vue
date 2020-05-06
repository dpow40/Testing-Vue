<template>
  <div id="app">
    <restaurant-screen></restaurant-screen>
  </div>
</template>

<script>
  import RestaurantScreen from "./components/RestaurantScreen";
  export default {
    name: 'App',
    components: {RestaurantScreen},
  };
</script>
