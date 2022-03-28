<template>
  <v-app>
    <v-app-bar app color="white" elevation="0" dark prominent>
      <img class="mt-3" alt="Vue logo" src="./assets/olga.png" width="150" />
      <div id="name">
        <div class="text-subtitle2">Olga Kiraga</div>
        <div class="text-caption">Specjalista ds. Ubezpieczeń i Inwestycji</div>
      </div>
      <v-spacer></v-spacer>
      <span class="mx-3 text-button" v-for="(link, idx) of links" :key="idx" @click="$router.push(link.path)">{{link.text}}</span>

    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    links: [
      {text: "Home", path: "/"},
      {text: "O Mnie", path: "/about"},
      {text: "Kontakt", path: "/contact"}
    ]
  }),
};
</script>
<style>
* {
  color: #c88b79;
}
#name{
  margin-top: 50px;
}
</style>
