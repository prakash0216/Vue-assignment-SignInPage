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
export default {
  // Component logic here
}
</script>

<style scoped>
/* Component-specific styles here */
.social-icons {
  display: flex; /* Already present */
  flex-direction: column; /* Already present */
  justify-content: center; /* Already present */
  align-items: center; /* Already present */
  text-align: center; /* Already present */
  background-color: rgb(32, 31, 31);
  height: 100px; /* Already present */
  width: 400px; /* Already present */
  /* Added property */
  flex-grow: 1;
  margin: 0;
}

.options,
.copyright {
  font-size: 10px; /* Set smaller font size */
  color: white;
}

.icon-container {
  margin: 5px 0;
}

.social-icons i {
  margin-right: 10px;
  color: white; /* Set icon color to white */
  font-size: 24px; /* Set larger icon size */
}
</style>
