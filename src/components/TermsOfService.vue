<template>
  <p class="terms" @click="showTermsModal" style="color: white">Read our Terms of Service</p>
</template>

<script>
export default {
  methods: {
    showTermsModal() {
      // Logic to show the terms modal or navigate to a separate terms page
      console.log('Showing terms modal or navigating to terms page')
    }
  }
}
</script>

<style scoped>
.terms {
  color: #007bff; /* Blue color for the clickable text */
  cursor: pointer; /* Change cursor to pointer on hover */
  margin-top: 20px;
  font-size: 12px;
  display: flex;
  justify-content: flex-start; /* Already present */
  align-items: start;
}
</style>
