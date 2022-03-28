<template>
<div>
  <quote></quote>
  <services></services>
</div>
  
</template>

<script>
import Quote from "../components/Quote.vue";
import Services from "../components/Services.vue";

export default {
  name: "HomeView",

  components: {
    Quote,
    Services,
  },
};
</script>
