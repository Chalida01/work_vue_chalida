<template>
  <div class="box1">
    <h1 class="text2">
      LOG IN
    </h1>
    <br>
    <v-text-field
      light
      label="Username"
      placeholder="ชื่อผู้ใช้ของคุณ"
      filled
    />
    <v-text-field
      light
      label="Password"
      placeholder="รหัสผ่านของคุณ"
      filled
    />
    <v-btn block color="amber darken-2" href="/home" dark>
      Log In
    </v-btn>
  </div>
</template>

<script>
export default {
  layout: 'theme2'
}
</script>

<style>
.box1{
  margin-top: 10%;
  padding: 50px;
}
.text2{
  font-family: "malgun gothic";
  font-size: 50px;
  color: #000;
}
</style>
