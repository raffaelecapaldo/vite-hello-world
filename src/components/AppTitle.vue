<template>
  <header>
    <h1 class="text-center">{{ title }}</h1>
  </header>
</template>

<script>
export default {
  name:"app-title",
  data() {

    return {
      title: "La mia prima app con Vite!"
    }
  }
}
</script>

<style lang="scss" scoped></style>