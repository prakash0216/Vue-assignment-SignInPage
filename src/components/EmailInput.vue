<template>
  <div class="form-group">
    <label for="email">Email:</label>
    <input
      type="email"
      id="email"
      v-model="email"
      required
      placeholder="Enter your email address"
    />
  </div>
</template>

<script>
export default {
  data() {
    return {
      email: ''
    }
  }
}
</script>
