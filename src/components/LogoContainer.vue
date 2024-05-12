<template>
  <div class="logo-container">
    <h1 class="logo-text" style="color: white">MGM</h1>
    <div class="logo-texts">
      <p class="logo-global" style="color: white">Global</p>
      <p class="logo-distribution" style="color: white">Distribution</p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.logo-container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
}

.logo-texts {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.logo-text {
  font-size: 2em;
  margin: 0;
  font-weight: bold;
}

.logo-global,
.logo-distribution {
  font-size: 1rem;
  margin: 0;
  font-weight: bold;
}

.logo-distribution {
  align-self: center;
}
</style>
