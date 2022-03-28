<template>
  <v-container class="d-flex align-center justify-center">
    <v-container>
        <v-row>
            <v-col>
                <div class="text-h4">Oferta</div>
            </v-col>
        </v-row>
      <v-row>
        <v-col v-for="(card, idx) of cards" :key="idx" cols="6">
          <v-card class="mx-auto" max-width="344">
            <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
            ></v-img>

            <v-card-title>
              {{ card.title }}
            </v-card-title>
            <v-card-subtitle>
                {{card.description}}
            </v-card-subtitle>

          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>
<script>
export default {
  data() {
    return {
      cards: [
        {
          title: "Polisa",
          description: "blablabla",
          img: "logo.png",
          show: false
        },
        {
          title: "Polisa",
          description: "blablabla",
          img: "logo.png",
          show: false
        },
        {
          title: "Polisa",
          description: "blablabla",
          img: "logo.png",
          show: false
        },
        {
          title: "Polisa",
          description: "blablabla",
          img: "logo.png",
          show: false
        }
      ]
    };
  }
};
</script>
