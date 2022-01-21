<template>
  <div>
    <img src="../assets/logo.png" alt="">
    <h2>Dog Name</h2>
    <button class="btn" @click="fetchDogs">Fetch Dog Image</button>
  </div>
</template>

<script>


export default {
  name: "Home",
  data(){
    return{
    count : 5

    }
  }, 

  methods:{
      fetchDogs(){
        this.count = this.count + 1
        console.log(this.count)
      }
  }
};
</script>

<style scoped>
.btn{
  height: 25px;
  width: 150px;
  background-color: aquamarine;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 15px;
  border-style : solid 

}
</style>>

