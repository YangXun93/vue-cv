<template>
  <!--v-app style=" background: linear-gradient(to bottom, #5B81FC, #DAE3FF);"-->
  <v-app>
    <v-content>
      <!--desktop version-->
      <v-row justify="center" class="d-none d-sm-flex">
        <v-col>
          <!--md = "10" lg="8"-->
          <v-parallax :src="require('@/assets/barBG.jpg')" height="100">
            <div style="height: 50px; color: black">
              <h1 align="center">2019</h1>
            </div>
          </v-parallax>
          <History19 />
          <v-parallax :src="require('@/assets/barBG.jpg')" height="100">
             <div style="height: 50px; color: black">
              <h1 align="center">2018</h1>
            </div>
          </v-parallax>
          <History18 />
          <v-parallax :src="require('@/assets/barBG.jpg')" height="100">
             <div style="height: 50px; color: black"></div>
          </v-parallax>
        </v-col>
      </v-row>

      <!--mobile version-->
      <v-row justify="center" class="d-flex d-sm-none">
        <v-col>
          <v-parallax :src="require('@/assets/barBG.jpg')" height="100">
             <div style="height: 50px; color: black">
              <h1 align="center">2019</h1>
            </div>
          </v-parallax>
          <History19Mobile />
          <v-parallax :src="require('@/assets/barBG.jpg')" height="100">
             <div style="height: 50px; color: black">
              <h1 align="center">2018</h1>
            </div>
          </v-parallax>
          <History18Mobile />

          <v-parallax :src="require('@/assets/barBG.jpg')" height="100">
             <div style="height: 50px; color: black"></div>
          </v-parallax>
        </v-col>
      </v-row>
    </v-content>
  </v-app>
</template>

<script>
import History18 from "./components/Timeline2018";
import History19 from "./components/Timeline2019";
import History18Mobile from "./components/Timeline2018Mobile";
import History19Mobile from "./components/Timeline2019Mobile";

export default {
  name: "App",
  components: {
    History18,
    History19,
    History18Mobile,
    History19Mobile
  },
  data: () => ({
    //
  })
};
</script>

<style>
a {
  text-decoration: none !important;
  color: white !important;
}
</style>