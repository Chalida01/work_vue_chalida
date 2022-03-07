<template>
  <div class="text-center">
    <v-img src="../img/home2.png" class="image" />
    <p class="text1">ระบบเยี่ยมบ้านนักเรียน</p>
    <v-btn color="amber darken-3" href="/login">
      login
    </v-btn>
  </div>
</template>
<script>
export default {
  layout: 'theme2'
}
</script>

// แบบเขียนcss
<style>
  .image{
    width: 120px;
    margin: auto;
    margin-top: 50%;
  }
  .text1{
    font-size: 24px;
    font-family: 'TH Baijam';
    color: black;
  }
</style>
