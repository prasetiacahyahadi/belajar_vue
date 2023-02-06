<script>
export default {
  // component options
  // declare some reactive state here.
  data(){
    return {
      message : 'Hello world !',
      counter: {
        count:0
      }
    }
  }
}
</script>

<template>
  <h1>{{message}}</h1>
  <p>Count is: {{ counter.count }}</p>
</template>