<template>
    <div>
        <h1>Restaurants</h1>
        <RestaurantList></RestaurantList>
    </div>
</template>

<script>
    import RestaurantList from "./RestaurantList";
    export default {
        name: "RestaurantScreen",
        components: {RestaurantList}
    }
</script>

<style scoped>

</style>
