<template>
  <div class="SearchBox">
    <input type="text" @input="search" v-model="searchValue" placeholder="Search Cities, Players and Nfts etc." :class="search">
  </div>
</template>

<script>
  export default {
  // name: 'SearchBox',
  data(){
    return {
      data(){
        return{
          // searchValue: ""
        }
      }
    }
  },
  methods: {
    search(){
      // this.$emit('handleSearch', this.searchValue)
    }
  }
}
</script>

<style scoped>
.SearchBox {
  /* margin-right: 2rem; */
  padding: 0.1rem;
}
input{
  border: 1px solid grey;
  border-radius: 10px;
  height: 100%;
  width:400px;
  outline: 0;
  font-size: 15px;
  padding: 10px;
  background-color: rgba(51, 51, 51, 1);
  float: right;
  transition: .3s;
  color: #fff;
}
input:hover, input:focus{
  background-color: white;
  color: #000;
}
h3{
  float: right;
  font-size: 20px;
  text-align: center;
  margin: 40px;
  top:0px;
}
</style>
