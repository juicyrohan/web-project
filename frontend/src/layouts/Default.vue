<template>
  <v-app>
    <v-navigation-drawer>
      <v-container fluid fill-height>
        <v-layout align-center justify-center>
          <v-flex xs12 sm10 md7 lg5>
            <slot />
          </v-flex>
        </v-layout>
      </v-container>
    </v-navigation-drawer>
    <v-app-bar>
    </v-app-bar>
    <v-content>
      <slot />
    </v-content>
    <v-footer>
      <v-spacer />
      <span class="white--text">&copy; 2022</span>
    </v-footer>
  </v-app>
</template>
