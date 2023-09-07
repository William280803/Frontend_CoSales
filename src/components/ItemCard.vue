<template>
    <div>
        <v-card class="ma-4" max-width="250">
            <v-img src="@/assets/item1.png" height="200px" cover></v-img>

            <v-card-title>
                Sneaker Keren
            </v-card-title>

            <v-card-subtitle>
                Harga Murah
            </v-card-subtitle>

            <v-card-actions>
                Harga Cuy
                <!-- <v-btn color="orange-lighten-2" variant="text">
                    Explore
                </v-btn>

                <v-spacer></v-spacer>

                <v-btn :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'" @click="show = !show"></v-btn> -->
            </v-card-actions>

            <v-expand-transition>
                <div v-show="show">
                    <v-divider></v-divider>

                    <v-card-text>
                        Googoo gagaa
                    </v-card-text>
                </div>
            </v-expand-transition>
        </v-card>
    </div>
</template>
<script>
export default {
    data: () => ({
        
        }),
}
</script>