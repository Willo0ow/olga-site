<template>
  <container class="about">
    <v-row class="mx-5">
      <v-col cols="4">
        <v-img src="@/assets/portret.jpg" width="100%"></v-img>
      </v-col>
      <v-col cols="8" class="text-section d-flex flex-column">
        <h3></h3>
        <v-spacer></v-spacer>
        <p class="font-weight-light description">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
          sollicitudin convallis nulla, ut aliquam nulla euismod eget. Proin
          mollis dolor ut sodales blandit. In semper neque sapien, non interdum
          diam eleifend quis. 
        </p>
        <p class="font-weight-light description">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
          sollicitudin convallis nulla, ut aliquam nulla euismod eget. Proin
          mollis dolor ut sodales blandit. In semper neque sapien, non interdum
          diam eleifend quis.
        </p>
        <p class="font-weight-light description">
          Nulla at urna nec ligula lobortis venenatis. Fusce
          bibendum vel dui eget suscipit. Sed semper tellus ac mauris
          scelerisque, vel venenatis odio vulputate. Nam vitae nunc placerat,
          placerat metus eu, luctus velit. Nunc tempus nunc nec est ultrices
          ultrices.
        </p>
        <v-spacer></v-spacer>
      </v-col>
    </v-row>
  </container>
</template>
<style>
.description {
  font-size: 1.1rem;
  line-height: 2.5rem;
}
.text-section{
  padding-right:150px;
}
</style>
