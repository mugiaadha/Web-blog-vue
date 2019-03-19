<template>
  <div class="content">
    <div class="md-layout">
      <div class="md-layout-item md-medium-size-100 md-size-66">
        <registration-form data-background-color="green"> </registration-form>
      </div>
      <div class="md-layout-item md-medium-size-100 md-size-33">
        <user-card> </user-card>
      </div>
    </div>
  </div>
</template>

<script>
import UserCard from "@/pages/UserProfile/UserCard.vue";
import RegistrationForm from "@/pages/SignUp/RegistrationForm.vue";

export default {
  components: {
    RegistrationForm,
    UserCard
  }
};
</script>
