<template>
  <div>
    <h1>{{ nome }}</h1>
    <p>{{ moltiplica(3, 2) }}</p>
  </div>
</template>

<script>
import MatUtils from "./utils/MatUtils";

export default {
  name: "DavideBonetti",
  mixins: [MatUtils],
  computed: {
    nome() {
      return "Davide Bonetti"
    }
  }
}
</script>

<style scoped>
h1 {
  /* font-size: smaller */
}
</style>
