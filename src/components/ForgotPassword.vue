<template>
  <div class="forgot-password">
    <a href="#" @click="showAlert">Forgot Password?</a>
  </div>
</template>

<script>
export default {
  methods: {
    showAlert() {
      alert('Forgot Password link clicked!')
    }
  }
}
</script>

<style scoped>
/* Add your styles here */
.forgot-password {
  font-size: 12px;
  display: flex; /* Enable flexbox */
  flex-direction: column; /* Stack elements vertically */
  align-items: flex-end;
  margin-bottom: 10px;
  margin-top: -27px;
  margin-right: 10px;
}
</style>
