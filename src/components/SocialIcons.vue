<template>
  <div class="social-icons">
    <p class="options">OTHER WAYS TO WATCH</p>
    <div class="icon-container">
      <i class="fab fa-apple fa-3x"></i>
      <i class="fab fa-app-store-ios fa-3x"></i>
      <i class="fab fa-amazon fa-3x"></i>
    </div>
    <p class="copyright">Search For AppleTV+ FYC on your App Store</p>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.social-icons {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: rgb(32, 31, 31);
  height: 100px;
  width: 400px;

  flex-grow: 1;
  margin: 0;
}

.options,
.copyright {
  font-size: 10px;
  color: white;
}

.icon-container {
  margin: 5px 0;
}

.social-icons i {
  margin-right: 10px;
  color: white;
  font-size: 24px;
}
</style>
