<script>
export default {
  data() {
    return {
      titleClass: 'title',
      pClass: 'p-class'
    }
  }
}
</script>

<template>
  <h1 :class="titleClass">Make me red</h1>
  <p :class="pClass">jadikan aku biru</p>
</template>

<style>
.title {
  color: red;
}
  .p-class{
    color: #003cff;
  }
</style>