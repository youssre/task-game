<template>
  <div class="navbar">
    <img src="@/assets/ho_me.png" alt="">
    <img src="@/assets/ho_lo.png" alt="">
    <img src="@/assets/ho_li.png" alt="">
  </div>
</template>

<script>
export default {
    name: "navComp",
}
</script>

<style scoped>
.navbar{
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #0f0f0f;
}
.navbar img{
    cursor: pointer;
}
</style>
