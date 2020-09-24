<template>
<div>
    <v-container>
        <v-carousel height="auto" width="1024" :show-arrows="false" hide-delimiters cycle :interval="6000">
            <v-carousel-item>
                <v-img src="@/assets/img/foto1.jpg" alt=""></v-img>
            </v-carousel-item>

            <v-carousel-item>
                <v-img src="@/assets/img/foto2.jpg" alt=""></v-img>
            </v-carousel-item>
            <v-carousel-item>
                <v-img src="@/assets/img/foto3.jpg" alt=""></v-img>
            </v-carousel-item>
            <v-carousel-item>
                <v-img src="@/assets/img/foto4.jpg" alt=""></v-img>
            </v-carousel-item>
        </v-carousel>

    </v-container>
    <!-- -->
</div>
</template>

<script>
export default {
    name: 'Carrusel',

    data() {
        return {

        }
    }
}
</script>

<style  scoped>

</style>
