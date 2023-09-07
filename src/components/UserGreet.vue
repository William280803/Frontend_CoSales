<template>
    <div>
        <div class="d-flex flex-row-reverse mb-6">
            <v-sheet class="ma-2 pa-5">Halo, <b>{{ nama }}</b></v-sheet>
        </div>
    </div>
</template>

<script>
export default{
    props: {
        nama: "",
    }
}
</script>

<style>

</style>