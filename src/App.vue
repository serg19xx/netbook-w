<script setup>
import { ref } from 'vue'

const value = ref('')
</script>

<template>
  <h1>TEST GIT</h1>
  <div class="text-3xl text-green-400 font-bold underline">IT SERG K</div>

  <div class="card flex justify-center">
    <Knob v-model="value" />
  </div>

  <div class="card flex flex-col items-center gap-4">
    <div class="flex flex-wrap gap-4 justify-center">
      <Button icon="pi pi-home" aria-label="Save" size="small" />
      <Button label="Profile" icon="pi pi-user" size="small" />
      <Button label="Save" icon="pi pi-check" iconPos="right" size="small" />
    </div>
    <div class="flex flex-wrap gap-4 justify-center">
      <Button label="Search" icon="pi pi-search" iconPos="top" size="small" />
      <Button label="Update" icon="pi pi-refresh" iconPos="bottom" />
    </div>
  </div>

  <div class="card flex justify-center flex-wrap gap-4">
    <Button label="Primary" size="large" />
    <Button label="Secondary" severity="secondary" />
    <Button label="Success" severity="success" />
    <Button label="Info" severity="info" />
    <Button label="Warn" severity="warn" />
    <Button label="Help" severity="help" />
    <Button label="Danger" severity="danger" />
    <Button label="Contrast" severity="contrast" />
  </div>
</template>

<style scoped></style>
