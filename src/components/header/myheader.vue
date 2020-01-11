<template>
<div class="header">
    <div class="content-wrapper">
      <div class="avatar">
        <img width="64" height="64" :src="seller.avatar">
      </div>
    </div>
    <div class="bulletin-wrapper"></div>
</div>
</template>
<script>
export default {
  name: 'myheader',
  props: {
    seller: {
    }
  }
}
</script>
<style lang='stylus' rel='stylesheet/stylus'>

</style>
