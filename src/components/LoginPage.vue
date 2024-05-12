<template>
  <div class="login-container">
    <form @submit.prevent="onSubmit">
      <LogoContainer></LogoContainer>
      <SignInText></SignInText>
      <email-input></email-input>
      <password-input></password-input>
      <forgot-password></forgot-password>
      <remember-me-checkbox></remember-me-checkbox>
      <sign-in-button></sign-in-button>
    </form>
    <TermsOfService></TermsOfService>
    <p v-if="successMessage" class="success-message">{{ successMessage }}</p>
    <Segment></Segment>
    <SocialIcons></SocialIcons>
  </div>
</template>

<script>
import LogoContainer from './LogoContainer.vue'
import EmailInput from './EmailInput.vue'
import PasswordInput from './PasswordInput.vue'
import RememberMeCheckbox from './RememberMeCheckbox.vue'
import SignInButton from './SignInButton.vue'
import ForgotPassword from './ForgotPassword.vue'
import TermsOfService from './TermsOfService.vue'
import SocialIcons from './SocialIcons.vue'
import Segment from './Segment.vue'
import SignInText from './SignInText.vue'

export default {
  components: {
    LogoContainer,
    EmailInput,
    PasswordInput,
    RememberMeCheckbox,
    SignInButton,
    ForgotPassword,
    TermsOfService,
    SocialIcons,
    Segment,
    SignInText
  },
  data() {
    return {
      successMessage: ''
    }
  },
  methods: {
    onSubmit() {
      console.log('Form Submitted')
      this.successMessage = 'Login successful. Redirecting...'
      setTimeout(() => {
        this.successMessage = ''
      }, 2000)
    }
  }
}
</script>

<style scoped>
.success-message {
  color: green;
  text-align: center;
  margin-top: 10px;
}
</style>
