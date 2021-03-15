<template>
  <div id="contract">
      <h2 class="title  has-text-centered"> {{ title }} </h2>
      <h3 class="title  is-primary"> {{ title }} </h3>
    
  </div>
</template>

<script>
export default {
  name: 'contract',
  props: {
    msg: String,
    title: String,
  },
  data: () => {
      return{
          loading:true,
          contracts:null,
          nftNumber: 0
      }
  },

  mounted(){
    this.loading = false
    this.contract = new ethers.Contract()

  },

  methods: {
      onClick() {

      },

      getNFTNumber(){

      }
  }
}
</script>