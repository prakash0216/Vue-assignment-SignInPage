<template>
  <div class="form-checkbox">
    <input type="checkbox" id="remember" v-model="remember" />
    <label for="remember" style="color: white; font-size: 12px"
      >Keep me signed in for 30 days</label
    >
  </div>
</template>

<script>
export default {
  data() {
    return {
      remember: false
    }
  }
}
</script>
