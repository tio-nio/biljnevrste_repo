<template>
  <div class="q-pa-md">
    <div class="q-gutter-y-md" style="max-width: 1600px">
      <q-tabs
        v-model="tab"
        class="bg-primary text-white shadow-2"
      >
        <q-tab name="unos" label="Unos Biljaka">
          <q-badge color="red" floating></q-badge>
        </q-tab>
        <q-tab name="pregled" label="Pregled Biljaka">
          <q-badge color="red" floating></q-badge>
        </q-tab>
        <q-tab name="kviz" label="Pregled rezultata kviza" />
      </q-tabs>
    </div>
  </div>
</template>
