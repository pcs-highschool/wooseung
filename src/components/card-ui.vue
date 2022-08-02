<template>
  <div class="amuz-card">
    <h2 v-if="menuTitle">
        {{ menuTitle }}
    </h2>
    <p v-else class="untitled">
        no title
    </p>
    <ul>
        <li>menu 1</li>
        <li>menu 2</li>
        <li>menu 3</li>
        <li>menu 4</li>
        <li>menu 5</li>
        <li>menu 6</li>
    </ul>
  </div>
</template>

<script>
export default {
    props : {
    menuTitle : String,
    menuCount : Number,
    backgroundcolor : String,
  },
}
</script>

<style>

</style>