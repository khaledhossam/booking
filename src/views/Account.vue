<template>
  <div >
     <nav-bar ></nav-bar>
    <container class="container-fluid">
    <b-form @submit="onSubmit" @reset="onReset" v-if="show">
      <b-form-group
        id="input-group-1"
        label="Email address:"
        label-for="input-1"
        description="We'll never share your email with anyone else."
      >
        <b-form-input
          id="input-1"
          v-model="form.email"
          type="email"
          required
          placeholder="Enter email"
        ></b-form-input>
      </b-form-group>


    <b-form @submit.stop.prevent>
        <label for="text-password">Password</label>
        <b-input type="password" id="text-password" aria-describedby="password-help-block"></b-input>
        <b-form-text id="password-help-block">
        Your password must be 8-20 characters long, contain letters and numbers, and must not
        contain spaces, special characters, or emoji.
        </b-form-text>
    </b-form>

    <div>
    <b-form @submit.stop.prevent>
        <label for="text-password">Password</label>
        <b-input type="password" id="text-password" aria-describedby="password-help-block"></b-input>
        <b-form-text id="password-help-block">
        Your password must be 8-20 characters long, contain letters and numbers, and must not
        contain spaces, special characters, or emoji.
        </b-form-text>
    </b-form>
    </div>


      <b-button type="submit" variant="primary">Log In</b-button>
      <b-button type="reset" variant="danger">Sign UP</b-button>
    </b-form>
    </container>
  </div>
</template>

<script>

import NavBar from '@/components/NavBar.vue'

  export default {

components: {
    "nav-bar":NavBar,
    
  },

    data() {
      return {
        form: {
          email: '',
          name: '',
          food: null,
          checked: []
        },
        foods: [{ text: 'Select One', value: null }, 'Carrots', 'Beans', 'Tomatoes', 'Corn'],
        show: true
      }
    },
    methods: {
      onSubmit(evt) {
        evt.preventDefault()
        alert(JSON.stringify(this.form))
      },
      onReset(evt) {
        evt.preventDefault()
        // Reset our form values
        this.form.email = ''
        this.form.checked = []
        // Trick to reset/clear native browser form validation state
        this.show = false
        this.$nextTick(() => {
          this.show = true
        })
      }
    }
  }
</script>

<style>

.container-fluid{
    float: right;
    width: 50%;
    padding-top: 50px;
  
}

</style>