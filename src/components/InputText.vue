<template>
  <v-form v-model="valid">
    <v-container>
      <v-row>
        <v-text-field
       
          :label="texto"
          required
        ></v-text-field>
      </v-row>
    </v-container>
  </v-form>
</template>

<script>
export default {
  props: {
    texto: {
      type: String,
      required: true,
    },
  },
  data() {
    return {

    };
  },
};
</script>