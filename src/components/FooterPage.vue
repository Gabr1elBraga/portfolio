<template>
    <v-footer dark padless>
        <v-card flat title class="black white--text py-5 px-5 text-center" width="100%">
            <v-row>
                <v-col cols="12" sm="4">
                    <v-card-text class="white--text pt-2">
                        <v-btn icon>
                            <v-icon color="#FAB005">
                                fas fa-microchip
                            </v-icon>
                        </v-btn>
                    </v-card-text>
                </v-col>
                <v-col cols="12" sm="4">
                    <v-card-text class="pt-2">
                        <v-btn v-for="icon in icons" :key="icon" class="mx-1 white--text" icon>
                        <v-icon size="24px">{{icon}}</v-icon>
                        </v-btn>
                    </v-card-text>
                </v-col>
                <v-col cols="12" sm="4">
                    <v-card-text class="pt-2">
                        <v-btn class="mx-1 white--text" icon>
                            <v-icon color="#FAB005">fa-brands fa-vuejs</v-icon>
                        </v-btn>
                        Created by Gabriel Braga
                    </v-card-text>
                </v-col>
            </v-row>
        </v-card>
    </v-footer>
</template>

<script>
export default {
    name: 'FooterPage',
    
    data:() =>({
        icons: ["mdi-twitter","mdi-facebook","mdi-instagram","mdi-github", "mdi-linkedin"]
    })
}
</script>

<style>
</style>