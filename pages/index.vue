<template>
  <v-container>
    <v-row justify="center">
      <v-col
        xl="6"
        lg="8"
        md="10"
        sm="12"
        class="vh-93 d-flex flex-column justify-center align-content-center"
      >
        <v-container class="text-center">
          <p class="text-h2 text-center">
            A digital consultancy driving <span class="red--text">real business results</span> through integrated digital solutions.
          </p>
          <v-btn
            class="mt-4"
            text
            large
            to="/about-us"
          >
            <v-icon>mdi-arrow-right</v-icon>
            <span class="font-weight-light ml-4">More About Us</span>
          </v-btn>
        </v-container>
      </v-col>
    </v-row>

    <v-row justify="center">
      <v-col
        xl="8"
        lg="12"
        md="12"
        sm="12"
        class="vh-93 d-flex flex-column justify-center align-content-center"
      >
        <v-container>
          <p class="text-h5 text-center font-weight-regular">
            Our Services
          </p>
          <p class="text-h2 text-center font-weight-light my-10">
            Core Capabilities
          </p>
          <v-row>
            <v-col class="pa-8">
              <v-icon size="100" color="green">
                mdi-palette-outline
              </v-icon>
              <p class="text-h5 font-weight-light mt-8">
                Web Design
              </p>
              <p class="subtitle-1 text-justify">
                We use data to determine where your most valuable customers lie,
                then adopt a fluid paid media strategy focused on generating results.
              </p>
              <v-btn
                class="mt-4"
                text
                large
              >
                <v-icon>mdi-arrow-right</v-icon>
                <span class="font-weight-light ml-4">Read More</span>
              </v-btn>
            </v-col>
            <v-col class="pa-8">
              <v-icon size="100" color="teal">
                mdi-application-braces-outline
              </v-icon>
              <p class="text-h5 font-weight-light mt-8">
                Web Application
              </p>
              <p class="subtitle-1 text-justify">
                All our solutions are based on actionable insights driven by a
                thorough research process – human-centred design, meaningfully
                crafted by local teams.
              </p>
              <v-btn
                class="mt-4"
                text
                large
              >
                <v-icon>mdi-arrow-right</v-icon>
                <span class="font-weight-light ml-4">Read More</span>
              </v-btn>
            </v-col>
            <v-col class="pa-8">
              <v-icon size="100" color="blue">
                mdi-web-check
              </v-icon>
              <p class="text-h5 font-weight-light mt-8">
                SEO
              </p>
              <p class="subtitle-1 text-justify">
                We utilise best-practise SEO underpinned by a consultative,
                data-driven approach focusing on the role SEO plays in an
                integrated digital strategy.
              </p>
              <v-btn
                class="mt-4"
                text
                large
              >
                <v-icon>mdi-arrow-right</v-icon>
                <span class="font-weight-light ml-4">Read More</span>
              </v-btn>
            </v-col>
          </v-row>
        </v-container>
      </v-col>
    </v-row>

    <v-row justify="center">
      <v-col
        xl="12"
        lg="12"
        md="12"
        sm="12"
        class="vh-93 d-flex flex-column justify-center align-content-center"
      >
        <v-container class="text-center">
          <p class="text-h2 text-center">
            If you’re looking to <span class="red--text">drive change</span> through an integrated digital strategy, you’re looking for us.
          </p>
        </v-container>
      </v-col>
    </v-row>

    <v-row justify="center">
      <v-col
        xl="10"
        lg="10"
        md="10"
        sm="12"
        class="vh-93 d-flex flex-column justify-center align-content-center"
      >
        <v-container>
          <p class="text-h5 text-center font-weight-regular">
            Our Technologies
          </p>
          <p class="text-h2 text-center font-weight-light my-10">
            Core Skills
          </p>
          <v-row justify="center">
            <v-col class="d-flex flex-column">
              <v-icon size="100" color="red">
                mdi-laravel
              </v-icon>
              <p class="text-h5 text-center font-weight-light mt-8">
                Laravel
              </p>
            </v-col>
            <v-col class="d-flex flex-column">
              <v-icon size="100" color="purple">
                mdi-dot-net
              </v-icon>
              <p class="text-h5 text-center font-weight-light mt-8">
                ASP.net
              </p>
            </v-col>
            <v-col class="d-flex flex-column">
              <v-icon size="100" color="green">
                mdi-nuxt
              </v-icon>
              <p class="text-h5 text-center font-weight-light mt-8">
                Nuxt.js
              </p>
            </v-col>
            <v-col class="d-flex flex-column">
              <v-icon size="100" color="green lighten-1">
                mdi-vuejs
              </v-icon>
              <p class="text-h5 text-center font-weight-light mt-8">
                Vue.js
              </p>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col class="d-flex flex-column">
              <v-icon size="100" color="blue">
                mdi-vuetify
              </v-icon>
              <p class="text-h5 text-center font-weight-light mt-8">
                Vuetify
              </p>
            </v-col>
            <v-col class="d-flex flex-column">
              <v-icon size="100" color="deep-purple">
                mdi-bootstrap
              </v-icon>
              <p class="text-h5 text-center font-weight-light mt-8">
                Bootstrap
              </p>
            </v-col>
            <v-col class="d-flex flex-column">
              <v-icon size="100" color="teal accent-3">
                mdi-bulma
              </v-icon>
              <p class="text-h5 text-center font-weight-light mt-8">
                Bulma
              </p>
            </v-col>
            <v-col class="d-flex flex-column">
              <v-icon size="100" color="light-blue">
                mdi-material-ui
              </v-icon>
              <p class="text-h5 text-center font-weight-light mt-8">
                Material UI
              </p>
            </v-col>
          </v-row>
        </v-container>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>
