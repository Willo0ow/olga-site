<template>
  <v-cntainer>
    <v-row>
      <v-col class="contact">
        <div v-for="(info, idx) of infos" :key="idx" class="py-0">
          <v-card-title class="py-2">{{ info.title }}</v-card-title>
          <v-card-subtitle class="py-0">{{ info.subtitle }}</v-card-subtitle>
        </div>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="contact">
        Spotkania odbywają się w biurze, u klienta, na mieście lub zdalnie.
      </v-col>
    </v-row>
  </v-cntainer>
</template>
<script>
export default {
  data() {
    return {
      infos: [
        {
          title: "kiraga.olga@aviva.com.pl",
          subtitle: "e-mail"
        },
        {
          title: "511 470 473",
          subtitle: "nr telefonu"
        },
        {
          title: "5851434511",
          subtitle: "NIP"
        },
                {
          title: "ul.Grunwaldzka 163 piętro 1, Gdańsk",
          subtitle: "Biuro"
        }
      ]
    };
  }
};
</script>
<style>
.contact{
  margin-top: 100px;
  padding-left: 64px;
}
</style>
