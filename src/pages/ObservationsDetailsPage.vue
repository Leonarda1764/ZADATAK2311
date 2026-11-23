<template>
  <q-page class="q-pa-md">
    <h1 class="text-h5">Detalji opažanja</h1>
    <p>Unesite detalja vašeg opažanja kako bismo imali bolji uvid u korisničko iskustvo.</p>
    <p>ID opažanja: {{ route.params.id }}</p>
  </q-page>
</template>

<script setup>
import { useRoute } from 'vue-router';
const route = useRoute();
</script>

