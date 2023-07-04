<template>
  <div>
    <h1>Home Page</h1>
  </div>
</template>

<script>
import { onDeactivated, onMounted } from 'vue';

export default {
    unmounted() {
        console.log("unmounted home page")
    },
    activated() {
        console.log("Home Component Activated")
    },
    deactivated() {
         console.log("deactivated  Home Page")
    }
};
</script>
