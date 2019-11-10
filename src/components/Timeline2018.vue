<template>
  <v-container>
    <v-timeline>
      <v-timeline-item color="blue" fill-dot left large icon="mdi-gamepad-variant-outline">
        <v-card >
          <v-img :src="require('../assets/31D.png')" class="my-1 white--text align-end" contain></v-img>
          <v-container>
            <h2>31D</h2>
            My first attempt to create a simple 2D platform game with Unity.
            <div class="my-2" align="right">
              <v-btn color="success">
                <a href="https://play.google.com/store/apps/details?id=com.YangXun.Game_31D" target="_blank">On Google Play</a>
              </v-btn>
            </div>
          </v-container>
        </v-card>
      </v-timeline-item>

      <v-timeline-item color="deep-purple" fill-dot right large icon="mdi-gamepad-variant-outline">
        <v-card>
          <v-img :src="require('../assets/5F.png')" class="my-3 white--text align-end" contain></v-img>
          <v-container>
            <h2>Run!</h2>
            My first attempt to create a simple 3D endless running with Unity.
            <div class="my-4" align="right">
              <v-btn color="success">
                <a href="https://play.google.com/store/apps/details?id=com.YangXun.Game_Run" target="_blank">On Google Play</a>
              </v-btn>
            </div>
          </v-container>
        </v-card>
      </v-timeline-item>

      <v-timeline-item color="blue" fill-dot left large icon="mdi-gamepad-variant-outline">
        <v-card>
          <v-img :src="require('../assets/4A.png')" class="my-3 white--text align-end" contain></v-img>
          <v-container>
            <h2>Endless ball</h2>
            Another 3D endless running with the character customizable by using collected coins in the game.
            <div class="my-4" align="right">
              <v-btn color="success">
                <a href="https://play.google.com/store/apps/details?id=com.YangXun.Game_Endless_Ball" target="_blank">On Google Play</a>
              </v-btn>
            </div>
          </v-container>
        </v-card>
      </v-timeline-item>
    </v-timeline>
  </v-container>
</template>