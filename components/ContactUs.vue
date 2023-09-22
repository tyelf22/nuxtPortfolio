<template>
    <iframe src="https://www.powr.io/form-builder/u/16acb237_1599444243#platform=iframe" style="width:100%;" height="680px" frameborder="0"></iframe>
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
            color="#F22F46"
            ></v-text-field>

            <v-text-field
            v-model="email"
            :rules="emailRules"
            label="E-mail"
            required
            name="user_email"
            color="#F22F46"
            ></v-text-field>

            <v-textarea
            clearable
            clear-icon="cancel"
            label="Message"
            :counter="500"
            color="#F22F46"
            ></v-textarea>

            <v-btn
            color="#F22F46"
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