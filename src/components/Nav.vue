<template>
<div>
    <v-app-bar app dark fixed>
        <v-app-bar-nav-icon class="hidden-md-and-up" @click="drawer=!drawer"></v-app-bar-nav-icon>
        <v-container class="hidden-sm-and-down container--fluid">
            <v-layout>
                <v-flex>
                    <v-btn color="secondary"><a href="/" class="white--text">
                            <v-icon>mdi-home</v-icon> Home
                        </a></v-btn>
                    <v-btn rounded><a href="/Biografia" class="white--text">Biografia</a></v-btn>
                    <v-btn rounded><a href="#" class="white--text">Esculturas</a></v-btn>
                    <v-btn rounded><a href="#" class="white--text">Dibujos</a></v-btn>
                    <v-btn rounded><a href="#" class="white--text">WorkShops</a></v-btn>
                    <v-btn rounded><a href="#" class="white--text">Proyecto con Niños</a></v-btn>
                    <v-btn rounded><a href="#" class="white--text">Contacto</a></v-btn>
                </v-flex>

            </v-layout>
        </v-container>
    </v-app-bar>

    <v-navigation-drawer v-model="drawer" app dark temporary class="mt-14">
        <v-container>
            <v-layout>
                <v-flex>
                    <v-btn color="secondary" rounded block><a href="/" class="white--text">
                            <v-icon>mdi-home</v-icon>
                        </a></v-btn>
                    <v-btn rounded block><a href="/Biografia" class="yellow--text">Biografia</a></v-btn>
                    <v-btn rounded block><a href="#" class="yellow--text">Esculturas</a></v-btn>
                    <v-btn rounded block><a href="#" class="yellow--text">Dibujos</a></v-btn>
                    <v-btn rounded block><a href="#" class="yellow--text">WorkShops</a></v-btn>
                    <v-btn rounded block><a href="#" class="yellow--text">Proyecto con Niños</a></v-btn>
                    <v-btn rounded block><a href="#" class="yellow--text">Contacto</a></v-btn>
                </v-flex>

            </v-layout>
        </v-container>
    </v-navigation-drawer>
</div>
</template>

<script>
export default {
    data() {
        return {
            drawer: false

        }
    }
}
</script>

<style scoped>
a {
    text-decoration: none;

}
</style>
