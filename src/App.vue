<template>
  <b-container fluid>
    <Header></Header>
    <b-container>
      <router-view/>
    </b-container>
  </b-container>
</template>

<script>
import Header from '@/components/Header'
export default {
  components:{
    Header: Header
  }
}
</script>

<style>
.container-fluid {
  padding-left: 0px !important;
  padding-right: 0px !important;
}
</style>
