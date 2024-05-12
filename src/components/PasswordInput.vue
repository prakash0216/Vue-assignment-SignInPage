<template>
  <div class="form-group">
    <label for="password">Password:</label>
    <input
      type="password"
      id="password"
      v-model="password"
      required
      placeholder="Enter your password"
    />
  </div>
</template>

<script>
export default {
  data() {
    return {
      password: ''
    }
  }
}
</script>
