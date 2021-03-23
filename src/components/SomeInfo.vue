<template>
    <v-container>
        <v-row>
            <v-col>
                <h3>{{ data }}</h3>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    name: "SomeInfo",
    props: {
        data: Number
    }
}
</script>

<style scoped>

</style>