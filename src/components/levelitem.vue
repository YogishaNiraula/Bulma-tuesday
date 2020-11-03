<template>
  <div class="container">
    <div class="level">
      <div class="level-left">
        <p class="level-item"><slot></slot></p>
      </div>
      <div class="level-right">
        <div class="media">
          <div class="media-content">
            <img class="image" src="https://i.imgur.com/UVtF5dW.jpg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.image {
  width: 420px;
  height: 420px;
}
.level-item {
  padding: 25px;
}
</style>
<script>
export default {
  name: "levelitem",
};
</script>