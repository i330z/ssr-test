<template>
  <v-row justify="center" align="center">
   <v-col>
     <h1>Home</h1>
     <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Labore dolor nostrum, cupiditate iste quis est natus earum. Dolor, nesciunt! Consectetur nihil assumenda quis eum autem, dolore eaque, suscipit impedit ipsam ducimus consequatur molestias tenetur tempora accusamus nesciunt distinctio praesentium animi architecto fugiat dicta modi voluptatem mollitia quae! Fuga vitae facere ipsam eligendi ratione nisi repellat quo qui incidunt, dolore earum unde quas esse rerum aliquam corporis aspernatur saepe repellendus, explicabo quod, minus minima sunt tempore! Voluptate aut nesciunt aperiam voluptatum.</p>
   <v-btn to="/pagetwo">Page Two</v-btn>
   </v-col>
  </v-row>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
