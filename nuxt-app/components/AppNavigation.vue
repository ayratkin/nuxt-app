<template>
  <div>
    <ul class="nav">
      <li>
        <NuxtLink to="/" class="item"> Main page</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/page1"> Page1</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/page2"> Page2</NuxtLink>
      </li>
    </ul>
  </div>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.nav {
  display: flex;
  list-style-type: none;

}
</style>