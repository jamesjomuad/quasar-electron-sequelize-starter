<template>
    <q-page class="flex flex-center">
        <img
            alt="Quasar logo"
            src="~assets/quasar-logo-vertical.svg"
            style="width: 200px; height: 200px"
        />
        <!--
        <q-btn label="Minimize" @click="minimize" />
        <q-btn label="DevTools" @click="devTools" />
        <q-btn label="Close" @click="close" /> -->
    </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
    name: "PageIndex",

    methods: {
        minimize() {
            App.minimize();
        },

        devTools() {
            App.devTools();
        },

        close() {
            App.close();
        },
    },
});
</script>
