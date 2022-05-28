<template>
<div>
<Header></Header>
<Nav></Nav>
<main class="main">
  <Nuxt />
</main>
<Footer></Footer>
</div>
</template>
<script>
export default {
    name: 'LayoutPage'
}
</script>

<style lang="scss" scoped>
  .main{
    width: 100%;
    // border: 1px solid black;
  }
</style>
