<template>
  <v-footer padless>
    <v-container
      fluid
      class="grey darken-4 white--text text-center px-0 py-15"
    >
      <v-row class="mx-15 px-15">
        <v-col
          xl="6"
          lg="6"
          md="12"
          sm="12"
          xs="12"
        >
          <h2 class="text-left font-weight-light text-space-3 mb-8">
            malikhain
          </h2>
          <p class="caption text-left ma-0">
            malikhain Digital Marketing Pty Ltd is a
            Philippines web design & digital marketing agency
          </p>
          <p class="caption text-left ma-0">
            <router-link to="/privacy-policy" class="caption text-decoration-none white--text">
              Privacy Policy
            </router-link> |
            <span class="caption">Copyright © {{ new Date().getFullYear() }} malikhain</span>
          </p>
        </v-col>
        <v-col
          xl="6"
          lg="6"
          md="12"
          sm="12"
          xs="12"
        >
          <div class="text-right mb-8">
            <v-btn
              v-for="icon in icons"
              :key="icon.value"
              class="white--text ml-4"
              icon
            >
              <v-icon :color="icon.color" size="24px">
                {{ icon.value }}
              </v-icon>
            </v-btn>
          </div>
          <div class="text-right mr-1">
            <router-link to="/web-design" class="overline text-decoration-none white--text mr-4">
              Design
            </router-link>
            <router-link to="/web-application" class="overline text-decoration-none white--text mr-4">
              Application
            </router-link>
            <router-link to="/seo" class="overline text-decoration-none white--text mr-4">
              SEO
            </router-link>
            <router-link to="/about-us" class="overline text-decoration-none white--text">
              About Us
            </router-link>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </v-footer>
</template>

<script>
export default {
  name: 'AppFooter',
  data: () => ({
    icons: [
      {
        value: 'mdi-facebook',
        color: 'blue',
      },
      {
        value: 'mdi-twitter',
        color: 'light-blue lighten-2',
      },
      {
        value: 'mdi-linkedin',
        color: 'blue darken-3',
      },
      {
        value: 'mdi-instagram',
        color: 'pink',
      },
    ],
  }),
};
</script>
