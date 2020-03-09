<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <h1>How to contribute?</h1>
      <h2>技術が好き!</h2>
      <p></p>
      <h2>今、興味があること</h2>
      <p></p>
      <h2>将来的なキャリア</h2>
      <p></p>
      <div id="app">
        <v-app id="inspire">
          <div>
            <v-stepper non-linear value="3">
              <v-stepper-header>
                <nuxt-link to="/aboutme">
                  <v-stepper-step editable step="1">
                    About me
                  </v-stepper-step>
                </nuxt-link>
                <v-divider></v-divider>
                <nuxt-link to="/why">
                  <v-stepper-step editable step="2">
                    Why Microsoft?
                  </v-stepper-step>
                </nuxt-link>
                <v-divider></v-divider>
                <nuxt-link to="/contribute">
                  <v-stepper-step step="3" editable>
                    How to contribute
                  </v-stepper-step>
                </nuxt-link>
              </v-stepper-header>
            </v-stepper>
          </div>
        </v-app>
      </div>
    </v-flex>
  </v-layout>
</template>

<style>
a {
  text-decoration: none;
}
</style>
