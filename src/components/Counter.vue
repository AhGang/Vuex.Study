<template>
<div>
    <button @click="calSum(1)">+</button>
     <input id="num1" v-model="this.$store.state.count">
    <button @click="calSum(-1)">-</button>
  </div>
</template>

<script>
export default {
 name: 'Counter',
 data(){
    return {
    }
  },
  computed:{

  },
  methods:{
  calSum(data){
      this.$store.commit('increaseCount',data)
     }
}
}
</script>

<style scoped>
</style>
