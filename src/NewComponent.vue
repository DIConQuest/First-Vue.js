<template>
  <div class="alert-box">
    <p>New component here</p>
  </div>
</template>

<script>
export default {
  name: "NewComponent",
};
</script>

<style>
.alert-box {
  width: 50vw;
  height: 40px;
  color: #eee;
  background: #3b3b3b;
  text-align: center;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
}
.alert-box > p {
  width: fit-content;
}
</style>
