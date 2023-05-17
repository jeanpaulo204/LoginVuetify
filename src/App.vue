<template>
  <v-app>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" sm="8" md="4">
        <v-card>
          <v-card-title class="justify-center">
          <v-col class="text-h3 text-center"> LOGIN </v-col>
          </v-card-title>
          <v-card-text>
            <v-form >
             <InputText texto="Nome do usúario"/>
              <!-- Fazer Outro Componente igual InputText Porem como  senha do usúario type dele é password exemplo type="password" e label dele vai ser sua senha aqui -->
              <!-- Aqui Vai ter um Botão usando Props Text igual InputText chamado Entrar -->
            </v-form>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
  </v-app>
</template>

<script>
 import InputText from './components/InputText.vue';

export default {
  name: 'App',

  components: {
   InputText
  },

  data: () => ({
    //
  }),
};
</script>
