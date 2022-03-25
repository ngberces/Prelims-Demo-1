<!--
Author: Berces, Neil Angelo G.
File Name: Profile.vue 
Description: Displays my Personal Information
-->
<template>
  <div id="profile">
    <div class="alert alert-primary" role="alert">
      <h1>{{ msg6 }}</h1>
      <p>Name: Berces, Neil Angelo G.</p>
      <p>Address: Babo Sacan, Porac, Pampanga</p>
      <p>Email: bercesneiil@gmail.com</p>
      <p>Phone Number: 09368987307</p>

    </div>
  </div>

</template>

<script>
export default {
  name: 'profile',
  data () {
    return{
      msg6: 'Personal Information'
    }
  }
}
</script>