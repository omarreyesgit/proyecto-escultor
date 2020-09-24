<template>
<div>
    <Carrusel></Carrusel>
    <v-container class="mt-1">
        <v-card shaped elevation="50" color="info">
            <v-card-text class="text-center">
                <h3> Deseo presentarles en este sitio web una retrospectiva de mi trabajo.

                    La muestra contiene ejemplos de mi oficio, realizados a partir de 1979 como alumno de la Escuela Profesional de Artes Plásticas "El Alba" en Holguín.

                    Seguidamente muestro trabajos de mi etapa de estudiante del Instituto Superior de Artes Plásticas de Berlin- Weissensee hasta la actualidad. </h3>
            </v-card-text>
        </v-card>
        <v-container>
            <v-row wrap>
                <v-col>
                    <v-card flat>
                        <v-img src="@/assets/img/card1.jpg"></v-img>
                    </v-card>
                </v-col>

                <v-col>
                    <v-card flat>
                        <v-img src="@/assets/img/card2.jpg"></v-img>
                    </v-card>
                </v-col>

                <v-col>
                    <v-card flat>
                        <v-img src="@/assets/img/card3.jpg"></v-img>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>

        <v-container>
            <v-row wrap>
                <v-col>
                    <v-card flat>
                        <v-img src="@/assets/img/card4.jpg"></v-img>
                    </v-card>
                </v-col>

                <v-col>
                    <v-card flat>
                        <v-img src="@/assets/img/card5.jpg"></v-img>
                    </v-card>
                </v-col>

                <v-col>
                    <v-card flat>
                        <v-img src="@/assets/img/card6.jpg"></v-img>
                    </v-card>
                </v-col>
            </v-row>
        </v-container>

    </v-container>
</div>
</template>

<script>
// @ is an alias to /src
import Carrusel from '@/components/Carrusel.vue'

export default {
    name: 'Home',
    components: {
        Carrusel
    },
    data() {
        return {

        }
    }
}
</script>

<style scoped>
h3 {
    color: white;
}
</style>
