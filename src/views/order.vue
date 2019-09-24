<template>
  <v-app id="warddoc.cloveropen.com">
    <Basepage />    
    <v-container fluid fill-height>
      <v-layout justify-start>
        <order />
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
import Basepage from "../components/Basepage";
import order from "../components/orderc";
export default {
  components: {
    Basepage,
    order
  }
};
</script>
