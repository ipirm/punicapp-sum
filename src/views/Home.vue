<template>
  <div class="home">
    <price-calculate></price-calculate>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import PriceCalculate from "../components/pages/PriceCalculate";

export default {
  name: 'Home',
  components: {
    PriceCalculate,
    HelloWorld
  }
}
</script>
