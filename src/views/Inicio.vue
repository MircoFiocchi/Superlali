<template>
<v-flex>
  <v-toolbar dark color="#006064">
    <v-toolbar-side-icon></v-toolbar-side-icon>

    <v-toolbar-title class="white--text">SUPERLALI</v-toolbar-title>

    <v-spacer></v-spacer>

    <v-btn icon>
      <v-icon>search</v-icon>
    </v-btn>

    <v-btn icon>
      <v-icon>person</v-icon>
    </v-btn>

    <template v-slot:extension>
      <v-toolbar-title class="white--text">Inicio de Sesion </v-toolbar-title>
    </template>

  </v-toolbar>
  <v-spacer></v-spacer>
   <v-layout position:Center  justify-center>

      <v-card ref="form">
        <v-card-text row>
          <v-text-field
            ref="gmail"
            v-model="name"
            label="Email"
            placeholder="pepito@gmail.com"
            required
          ></v-text-field>
          <v-text-field
            ref="contrasena"
            v-model="contrasena"
            label="Contrasena"
            placeholder="******"
            counter="25"
            required
          ></v-text-field>

        </v-card-text>
        <v-btn block color="#006064" >Ingresar </v-btn>
      
        <v-btn block color="#4DB6AC" >Registrarse </v-btn>
        
      </v-card>

  </v-layout>
</v-flex>
</template>