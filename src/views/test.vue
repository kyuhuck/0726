<template>
  <div>
    <h1>여기는 라디오입니다2222</h1>
    {{test}}



  </div>

</template>

<script>
  import {mapState} from 'vuex';
  export  default {
    name : "App",
    data(){
      return{

      }

    },
    computed:{
      ...mapState({
        //test : state => state.test
        //test: 'test'

        //testlist(state){
          //this.test = state

          //return state.test;
        //}

        test : state => state.test






      })

    }
  }

</script>
