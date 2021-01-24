<template>
  <div class="home">
    <hello-world></hello-world>
    <!-- <SignUpForm /> -->
    <sign-up-form></sign-up-form>
  </div>
</template>
<script lang="ts">
import Vue from 'vue';
import HelloWorld from '../components/HelloWorld.vue';
import SignUpForm from '../components/SignUpForm.vue';

export default Vue.extend({
  components: {
    HelloWorld,
    SignUpForm,
  },
});
</script>
