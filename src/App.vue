<template>
    <v-app align="center">
        <main-header></main-header>
        <v-main>
            <some-info :data="myNum"></some-info>
        </v-main>
        <main-footer></main-footer>
    </v-app>
</template>

<script>
import MainHeader from "@/components/MainHeader";
import MainFooter from "@/components/MainFooter";
import SomeInfo from "@/components/SomeInfo";

export default {
    name: 'App',
    components: {
        MainHeader,
        MainFooter,
        SomeInfo
    },
    
    data() {
        return {
            myNum: 21,
        }
    },
};
</script>
