<template>
  <div class="about">
    <v-container fluid class="container">
      <!-- Spacer -->
      <v-row class="ma-md-10"></v-row>
      <v-row class="ma-md-10"></v-row>

      <!-- mast head -->
      <v-row class="px-md-16 px-sm-16" justify="center">
        <v-col sm="12" md="5" align-self="center">
          <div class="pa-2">
            <h1 class="text-h2 pb-10">Empower Reality</h1>
            Seek is different. In our world there are no apps needed. There is
            seamless integration with every device, channel and metaverse. There
            are no walls between physical and digital.
            <br />
            <br />
            <v-btn elevation="3">Book a Demo</v-btn>
          </div>
        </v-col>
        <v-col cols="12" sm="12" md="4">
          <div class="center">
            <v-img
              :aspect-ratio="1"
              src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"
            ></v-img>
            <br />
            <v-btn elevation="3" class="center">Adventure Awaits</v-btn>
          </div>
        </v-col>
      </v-row>

      <!-- Spacer -->
      <v-row class="ma-10"></v-row>
      <v-row class="ma-10"></v-row>
      <v-row class="ma-10"></v-row>

      <!-- Clients -->
      <v-row>
        <v-col cols="6" md="2" sm="4" s="4" v-for="n in 6" :key="n">
          <v-img
            :aspect-ratio="16 / 9"
            src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"
          ></v-img
        ></v-col>
      </v-row>

      <!-- Facts -->
      <v-row class="mt-16">
        <v-col sm="12" md="12" no-gutters>
          <div>
            <v-img
              :aspect-ratio="16 / 6"
              src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"
            >
              <v-overlay absolute>
                <h1 class="text-md-h1 text-sm-h2 text-h4 text-center">
                  Inscrease Awesomeness by <br />
                  256%
                </h1>
              </v-overlay>
            </v-img>
          </div>
        </v-col>
      </v-row>

      <!-- Spacer -->
      <v-row class="ma-10"></v-row>

      <!-- Clients -->
      <v-row>
        <v-col cols="6" md="2" sm="4" s="4" v-for="n in 6" :key="n">
          <v-img
            :aspect-ratio="16 / 9"
            src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"
          ></v-img
        ></v-col>
      </v-row>

      <!-- Spacer -->
      <v-row class="ma-10"></v-row>
      <v-row class="ma-10"></v-row>

      <!-- products -->
      <v-row class="display" justify="center">
        <v-col cols="12" md="4" sm="6">
          <v-img
            :aspect-ratio="9 / 10"
            src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"
          ></v-img
        ></v-col>
        <v-col cols="12" md="4" sm="6" align-self="center">
          <h1>SeekXR Platform</h1>
          <h2>Enterprise 3D Asset Management</h2>
          <p>
            Businesses of all sizes require a place for their 3D models to be
            managed, have their quality controlled, and verified for channel
            deployment. With Seek's core platform, controlling 3D models has
            never been easier.
          </p>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "test-view",
  data: () => ({
    alignments: ["start", "center", "end"],
  }),
};
</script>

<style scoped>
.center {
  text-align: center;
}
</style>
