<template>
    <div>
        <v-carousel cycle height="400" hide-delimiter-background hide-delimiters show-arrows="hover">
            <v-carousel-item v-for="(slide, i) in slides" :key="i">
                <v-sheet :color="colors[i]" height="100%" width="100%">
                    <div class="d-flex fill-height justify-center align-center">
                        <div class="text-h2">
                            {{ slide }}
                        </div>
                    </div>
                </v-sheet>
            </v-carousel-item>
        </v-carousel>
    </div>
</template>
<script>
export default {
    data() {
        return {
            colors: [
                'indigo',
                'warning',
                'pink darken-2',
                'red lighten-1',
                'deep-purple accent-4',
            ],
            slides: [
                'First',
                'Second',
                'Third',
                'Fourth',
                'Fifth',
            ],
        }
    },
}
</script>

