<template>
<div>
    <v-responsive
    class="mx-0"
    max-width="300"
  > 
  <v-text-field label="Поиск" variant="solo-filled"></v-text-field>
</v-responsive>

<v-container grid-list-md text-xs-center>
    <v-layout row wrap>
      <v-flex v-for="i in 3" :key="`4${i}`" xs4>
        <v-card
          class="mx-auto"
          max-width="344"
          hover
         >
            <v-card-item>
            <v-card-title>
                Название лиги
             </v-card-title>
              </v-card-item>
             <v-card-text>
                  Страна
              </v-card-text>
        </v-card>
      </v-flex>
      <v-flex v-for="i in 3" :key="`4${i}`" xs4>
        <v-card
          class="mx-auto"
          max-width="344"
          hover
         >
            <v-card-item>
            <v-card-title>
                Название лиги
             </v-card-title>
              </v-card-item>
             <v-card-text>
                  Страна
              </v-card-text>
        </v-card>
      </v-flex>
      <v-flex v-for="i in 3" :key="`4${i}`" xs4>
        <v-card
          class="mx-auto"
          max-width="344"
          hover
         >
            <v-card-item>
            <v-card-title>
                Название лиги
             </v-card-title>
              </v-card-item>
             <v-card-text>
                  Страна
              </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>

  
        <p>Это компетишн</p>
   

</div>
</template>
