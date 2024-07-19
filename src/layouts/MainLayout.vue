<template>
  <q-layout view="hHh lpR fFf">
    <q-header reveal class="bg-primary text-white">
      <q-toolbar>
        <q-toolbar-title> Expressive Writer </q-toolbar-title>
        <q-btn-group push glossy>
          <q-btn
            color="grey"
            text-color="black"
            label="Timeline"
            icon="timeline"
          />
          <q-btn color="grey" text-color="black" label="List" icon="list" />
          <q-btn
            color="grey"
            text-color="black"
            label="Calendar"
            icon="calendar_month"
          />
        </q-btn-group>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <div class="q-pa-md q-gutter-y-md column items-start"></div>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup lang="ts">
defineOptions({
  name: 'MainLayout',
});
</script>
