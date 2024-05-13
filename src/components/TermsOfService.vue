<template>
  <p class="terms" @click="showTermsModal" style="color: white">Read our Terms of Service</p>
</template>

<script>
export default {
  methods: {
    showTermsModal() {
      console.log('Showing terms modal or navigating to terms page')
    }
  }
}
</script>

<style scoped>
.terms {
  color: #007bff;
  cursor: pointer;
  margin-top: 20px;
  margin-right: 120px;
  font-size: 12px;
  display: flex;
  justify-content: flex-start;
  align-items: start;
}
</style>
