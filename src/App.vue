<template>
  <v-app>
    <!-- Header Bölümü -->

    <!-- Header Bölümü END -->

    <!-- Container -->
    <v-content>
      <v-container>
        <v-row class="mb-4">
          <v-col
            xs="12"
            sm="6"
            md="4"
            lg="3"
            xl="2"
            v-for="(item, index) in 3"
            :key="index"
          >
            <v-card class="elevation-0">
              <v-img
                src="https://raw.githubusercontent.com/SelimPolat16/twitch-clone-vue/vue_eskiversion/src/images/kodbilbakkal.png"
              />

              <v-card-subtitle></v-card-subtitle>
              <v-avatar>
                <img
                  src="https://static-cdn.jtvnw.net/jtv_user_pictures/1872225b-c797-4b35-b172-007c1a1fdb66-profile_image-70x70.png"
                  alt="Kodbilen"
                />
              </v-avatar>
              <v-card-text
                ><div class="float-left">
                  <a href="#"> Kodbilen Yayında | !çöp !düş</a>
                </div>
                <div>Kodbilen</div></v-card-text
              >
              <v-card-actions> </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
    <!-- Container END -->
  </v-app>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    //
  })
}
</script>

<style scoped>
img {
  max-width: 100%;
  vertical-align: top;
  cursor: pointer;
}
a {
  color: inherit;
  text-decoration: none;
  cursor: pointer;
}
a:hover {
  color: rgb(137, 71, 234);
  color: var(--color-text-link);
  cursor: pointer;
}
</style>
