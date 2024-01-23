<template>
    <div>
        <form>
        <input  type="text" v-model="username"  name="" id="" placeholder="username">
        <input  type="password" v-model="password" name="" id="" placeholder="password">
        <button>login</button>
        </form>
        <p>username={{ username }} </p>
        <p>password={{ password }} </p>
    </div>
</template>


<script>
      export default{
        data(){
          return{
            username:"",
            password:""
          }
        }
    }
   
</script>
<style scoped>

</style>