<template>
  <div>
    <h1>hi</h1>
    <hr />
    <card-ui :menuTitle="'test title'" :menuCount="2" :backgroundColor="'red'" />
    <card-ui />
    <card-ui :menuTitle="'test title'" :menuCount="2" :backgroundColor="'red'" />
    <card-ui />
    <card-ui />
    <card-ui />
    <card-ui :menuCount="5"/>
    <card-ui />
    <card-ui :menuTitle="'other title'" />
    <card-ui />
  </div>
</template>

<script>
// define > 정의
import CardUi from './components/card-ui.vue'
export default {
  components: { CardUi },

}
</script>

<style>

</style>