<template>
  <button class="btn btn-primary">
      <i class="fa fa-2x" :class="icon"></i>
  </button>
</template>

<script>
export default {
    props:{
        icon:{
            type: String,
            default: 'fa-plus'
        }
    },
    // computed:{
    //     generateClassCSS(){
    //         let txtClass="fa fa-2x "

    //         console.log(this)
    //         txtClass += this.icon ? "fa-save" : "fa-plus"
    //         return txtClass
    //     }
    // }

}
</script>

<style lang="scss" scoped>
    button{
        border-radius: 100%;
        bottom: 20px;
        height:80px;
        position:fixed;
        right: 20px;
        width:80px;
    }
</style>