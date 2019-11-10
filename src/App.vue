<template>

  <v-app style=" background: linear-gradient(to bottom, #8DF86A , #D4FFAC);">
    <v-content>

       <v-row justify="center">
       <v-col md = "10" lg="8">
          <h1 align="center">2018</h1>
      <History18/>
      <h1 align="center">2019</h1>
       <History19/>
         <h1 align="center">Today</h1><br>
         </v-col>
       </v-row>
    </v-content>
  </v-app>

</template>

<script>
import History18 from "./components/Timeline2018";
import History19 from "./components/Timeline2019";

export default {
  name: "App",
  components: {
    History18,
    History19
  },
  data: () => ({
    //
  })
};
</script>

<style>
a{
    text-decoration: none !important;
    color: white !important;
  }
</style>