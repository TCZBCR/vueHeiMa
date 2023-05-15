<template>
    <div id="app">

<!--       <h1>{{message}}</h1>-->

<!--<element-view></element-view>-->

        <emp-view></emp-view>
    </div>
</template>
<script>



/*import ElementView from "@/views/element/ElementView.vue";*/
import EmpView from "@/views/tlias/EmpView.vue";

export default {
    components: {EmpView},

    data() {
       return {
            message:"hello vue"
        }
    }
}
</script>
<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}

nav {
    padding: 30px;
}

nav a {
    font-weight: bold;
    color: #2c3e50;
}

nav a.router-link-exact-active {
    color: #42b983;
}
</style>
