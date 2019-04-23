<template>
  <div class="dashboard">
    <h1 class="subheading grey--text">Dashboard</h1>

    <v-container class="my-5">

      <v-card flat class="pa-3">
        <v-layout row wrap>
          <v-flex xs12 md6>
            <div class="caption grey--text">Project title</div>
            <div>Create a website</div>
          </v-flex>
          <v-flex xs6 md2 sm4>
            <div class="caption grey--text">Person</div>
            <div>The net ninja</div>
          </v-flex>
          <v-flex xs6 md2 sm4>
            <div class="caption grey--text">Due by</div>
            <div>1st Jan 2019</div>
          </v-flex>
          <v-flex xs2 md2 sm4>
            <div class="caption grey--text">Status</div>
            <div>Ongoing</div>
          </v-flex>
        </v-layout>
      </v-card>

    </v-container>
  </div>
</template>

<script>
  export default {
  }
</script>
