<template>
  <div class="hello">
     <mt-button @click.native="handleClick">按钮</mt-button>
  </div>
</template>

<script>
export default {
  data () {
    return {

    }
  },
  methods:{
     handleClick() {
      this.$toast('Hello world!')
    }
  }
}
</script>

<style >

</style>
