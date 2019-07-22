<template>
  <div>
    <input v-model.number="inputNum">
    <div>
     <Counter></Counter>
    </div>
  </div>
</template>

<script>
import Counter from './components/Counter'

export default {
  components:{
    Counter
  },
  name: 'app',
  data(){
    return {
      inputNum : 0,

    }
  },
  watch: {
   
  },
  methods:{
   
  }
}
</script>
