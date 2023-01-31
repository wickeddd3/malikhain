<template>
  <v-app-bar
    app
    fixed
    elevate-on-scroll
    color="white"
    class="px-15"
  >
    <v-toolbar-title
      tag="router-link"
      to="/"
      class="font-weight-light text-decoration-none black--text text-space-3 ml-15"
    >
      malikhain
    </v-toolbar-title>

    <v-spacer />

    <v-btn to="/web-design" text>
      Web Design
    </v-btn>

    <v-btn to="/web-application" text>
      Web Application
    </v-btn>

    <v-btn to="/seo" text>
      SEO
    </v-btn>

    <v-btn icon class="ml-4 mr-15">
      <v-icon>mdi-sort-variant</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: 'AppBar',
};
</script>
