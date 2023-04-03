<template>
    <v-row align="center" justify="center">
        <v-col cols="12" md="3">
            <v-card color="#212121" class="py-6 px-8" elevation="6">
                <v-row align="center" justify="center">
                    <v-col cols="12">
                        <v-img :src="require('../assets/images/menu.png')" contain height="70"></v-img>
                        <v-card-text class="text-center font-weight-regular text-h6 py-0">Add widgets</v-card-text>
                    </v-col>
                </v-row>
            </v-card>
        </v-col>
        <v-col cols="12" md="6">
            <v-card color="#3F52C8" class="px-4 pt-5 pb-5" elevation="6">
                <v-row align="center">
                    <v-img :src="require('../assets/images/robot.png')" contain height="130" max-width="130"></v-img>
                    <v-col cols="6" justify="center" class="mb-2 ml-4">
                        <v-card-text class="text-h5 font-weight-regular pb-1">Hello, Admin Core</v-card-text>
                        <v-card-text class="text-p py-0 text-left">Welcome in the system</v-card-text>
                    </v-col>
                </v-row>
            </v-card>
        </v-col>
        <v-col cols="12" md="3">
            <v-card color="#212121" class="py-6 px-8" elevation="6">
                <v-row align="center">
                    <v-img :src="require('../assets/images/dollar.png')" contain height="80" max-width="80"></v-img>
                    <v-col>
                        <v-card-text class="pa-0 text-subtitle-1">Reward</v-card-text>
                        <v-card-text class="pa-0 text-h3 font-weight-bold green--text">123</v-card-text>
                        <v-card-text class="pa-0">Points Credited</v-card-text>
                    </v-col>
                </v-row>
            </v-card>
        </v-col>
    </v-row>
</template>

<script>
export default {

}
</script>

<style>

</style>