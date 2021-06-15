<template>
  <div class="home">
    <h1>Vārtu ražotne</h1>

    <Cards />
  </div>
</template>

<script>
import Cards from "@/components/Cards.vue"
export default {
  name: "home",
  components: {
    Cards
  }
}
</script>