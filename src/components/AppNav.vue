<script>
import { store } from "../components/store";
export default {
    data() {
        return {
            store,
        }
    },
}
</script>
<template>
     <div id="nav">
        <img src="../assets/img/Yu-Gi-Oh_Logo.webp" alt="">
        <h1>Yu-gi-oh Api</h1>

    </div>
</template>
<style lang="scss" scoped>
#nav {
    display: flex;
    align-items: center;
    height: 180px;
    background-color: white;
    img {
        height: 50%;
    }
    h1 {
        padding-left: 50px;
        color: black;
        font-size: 4em;
       
    }
}
</style>