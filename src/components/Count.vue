<template>
  <div style="margin-top : 100px;">
      <h2>Count 예제</h2>
      <b>count : {{ this.$store.state.count }}</b><br>
      <input type="button" @click="increment()" value="increment"/>
      <input type="button" @click="decrement()" value="decrement"/>
  </div>
</template>

<script>
export default {
    data(){
        return {

        }
    },
    created: function(){
        console.log(this.$store)
    },
    methods: {
        increment: function(){
            this.$store.commit('increment')
        },
        decrement : function(){
            this.$store.commit('decrement')
        }
    }

}
</script>

<style>

</style>