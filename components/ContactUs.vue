<template>
    <div class="powr-form-builder form" id="3a4a9d97_1599422770"></div>
    <!-- <v-app>
        <v-form
            ref="form"
            v-model="valid"
            @submit.prevent="sendEmail"
            
        >
            <v-text-field
            v-model="name"
            :counter="40"
            :rules="nameRules"
            label="Name"
            required
            name="user_name"
            color="#ea178c"
            ></v-text-field>

            <v-text-field
            v-model="email"
            :rules="emailRules"
            label="E-mail"
            required
            name="user_email"
            color="#ea178c"
            ></v-text-field>

            <v-textarea
            clearable
            clear-icon="cancel"
            label="Message"
            :counter="500"
            color="#ea178c"
            ></v-textarea>

            <v-btn
            color="#ea178c"
            class="mr-4"
            outlined
            rounded
            :disabled="!valid"
            >
            Send
            </v-btn>

            <v-btn
            color="error"
            outlined
            class="mr-4"
            rounded
            @click="reset"
            >
            Reset
            </v-btn>
        </v-form>
  </v-app> -->
</template>

<script>

export default {
    data: () => ({
    //     valid: false,
    //   name: '',
    //   nameRules: [
    //     v => !!v || 'Name is required',
    //     v => (v && v.length <= 40) || 'Name must be less than 40 characters',
    //   ],
    //   email: '',
    //   emailRules: [
    //     v => !!v || 'E-mail is required',
    //     v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
    //   ],
    }),
  methods: {
    // sendEmail: (e) => {
    //   emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', e.target, 'YOUR_USER_ID')
    //     .then((result) => {
    //         console.log('SUCCESS!', result.status, result.text);
    //     }, (error) => {
    //         console.log('FAILED...', error);
    //     });
    // },
    // reset () {
    // this.$refs.form.reset()
    // },
  },
}
</script>

<style scoped>
  .form {
    z-index: 3;
  }

</style>