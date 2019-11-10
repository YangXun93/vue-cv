<template>
  <v-container>
    <v-timeline>

      <v-timeline-item
        color="#64B5F6"
        right
        large
        icon="mdi-school"
      >
        <template v-slot:opposite><h3  style="color: #64B5F6">February</h3></template>
         <v-container>
        <h3 style="font-weight:normal;">Graduation in computer science at Università degli Studi di Milano-Bicocca</h3>
         </v-container>
      </v-timeline-item>

      <v-timeline-item
        color="#1E88E5"
        right
        large
        icon="mdi-language-java"
      >
        <template v-slot:opposite><h3  style="color: #1E88E5">April</h3></template>
         <v-container>
            <h3 style="font-weight:normal;">Training at Beije Consulting S.r.l as Java back-end developer</h3>
         </v-container>      
      </v-timeline-item>

      <v-timeline-item
        color="#1565C0"
        right
        large
        icon="mdi-briefcase"
      >
        <template v-slot:opposite><h3  style="color: #1565C0">June</h3></template>
         <v-container>
            <h3 style="font-weight:normal;">Got Java Certification OCA (Oracle Certified Associate)</h3><br>
            <h3 style="font-weight:normal;">Start a career as a junior developer at Beije Consulting S.r.l</h3>
         </v-container>
      </v-timeline-item>

      <v-timeline-item
        color="#303F9F"
        right
        large
        icon="mdi-briefcase"
      >
        <template v-slot:opposite><h3  style="color: #303F9F">June - September</h3></template>
         <v-container>
            <h3 style="font-weight:normal;">Work at first customer: Blue Reply</h3>
         </v-container>
      </v-timeline-item>


      <v-timeline-item
        color="#1A237E"
        right
        large
        icon="mdi-briefcase"
      >
        <template v-slot:opposite><h3  style="color: #1A237E">October - Today</h3></template>
         <v-container>
            <h3 style="font-weight:normal;">Star work at customer: Healty Reply</h3>
         </v-container>
      </v-timeline-item>

    </v-timeline>
  </v-container>
</template>