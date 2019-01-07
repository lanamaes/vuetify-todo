<template>
  <div class="dashboard">
    <h1 class="subheading grey--text">Dashboard</h1>

    <!-- lesson 12 padding and margin -->
    <v-container class="my-5">

      <!--lesson 13/14 grid system -->
      <v-card flat class="pa-3">
        <v-layout row wrap>
          <v-flex xs12 md6>
            <div class="caption grey--text">Project Title</div>
            <div>Create a new website</div>
          </v-flex>
          <v-flex xs6 sm4 md2>
            <div class="caption grey--text">Person</div>
            <div>Lana</div>
          </v-flex>
          <v-flex xs6 sm4 md2>
            <div class="caption grey--text">Due by</div>
            <div>1st Jan 2020</div>
          </v-flex>
          <v-flex xs2 sm4 md2>
            <div class="caption grey--text">Status</div>
            <div>ongoing</div>
          </v-flex>
        </v-layout>
      </v-card>

    </v-container>

  </div>
</template>

<script>

    export default {
        components: {

        }
    }
</script>
