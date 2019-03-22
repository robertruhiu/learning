<template>
    <div>
      <h1>{{message}}</h1>
      <app-input :msg="message" @messageChanged ="message = $event"></app-input>
    </div>
</template>

<script>
  import Input from './Input'
    export default {
        name: "message",
      components:{
          'app-input': Input
      },
      data(){
          return {
            message: 'Great message'
          }
      }

    }
</script>

<style scoped>

</style>
