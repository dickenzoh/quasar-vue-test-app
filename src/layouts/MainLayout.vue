<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="text-center q-pa-md" elevated>
      <q-item-label>
        Header
      </q-item-label>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="text-center q-pa-md" elevated>
      <div>Footer </div>
    </q-footer>
  </q-layout>
</template>

<script setup>

defineOptions({
  name: 'MainLayout'
})

</script>
