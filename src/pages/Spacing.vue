<template>
  <q-page class="q-pa-xl">
    <section class="q-mb-xl">
      <div class="text-h4">Spacing</div>
      <q-separator class="q-my-md"></q-separator>
      <div class="bg-primary q-pa-xs q-mt-md">
        <div class="bg-dark text-white">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea,
          explicabo. Ad sapiente autem debitis, nesciunt aperiam rerum
          temporibus maiores vitae voluptatum inventore aspernatur consequuntur
          voluptates corporis ex nisi esse repellendus.
        </div>
      </div>
      <div class="bg-primary q-pa-md q-mt-md">
        <div class="bg-dark text-white">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea,
          explicabo. Ad sapiente autem debitis, nesciunt aperiam rerum
          temporibus maiores vitae voluptatum inventore aspernatur consequuntur
          voluptates corporis ex nisi esse repellendus.
        </div>
      </div>
      <div class="bg-primary q-pa-lg q-mt-md">
        <div class="bg-dark text-white">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea,
          explicabo. Ad sapiente autem debitis, nesciunt aperiam rerum
          temporibus maiores vitae voluptatum inventore aspernatur consequuntur
          voluptates corporis ex nisi esse repellendus.
        </div>
      </div>
      <div class="bg-primary q-pa-xl q-mt-md">
        <div class="bg-dark text-white">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea,
          explicabo. Ad sapiente autem debitis, nesciunt aperiam rerum
          temporibus maiores vitae voluptatum inventore aspernatur consequuntur
          voluptates corporis ex nisi esse repellendus.
        </div>
      </div>
      <div
        class="bg-primary q-mt-md flex items-center justify-center"
        style="width: 100%; height: 400px"
      >
        <div class="bg-dark text-white" style="width: 100px; height: 100px">
          Hello
        </div>
      </div>
    </section>
    <section class="q-mb-xl">
      <div class="text-h4">Components</div>
      <q-separator class="q-my-md"></q-separator>
      <q-card
        class="my-card bg-secondary text-white q-mx-auto"
        style="width: 400px"
      >
        <q-card-section>
          <div class="text-h6">Our Changing Planet</div>
          <div class="text-subtitle2">by John Doe</div>
        </q-card-section>

        <q-card-section>
          {{ lorem }}
        </q-card-section>

        <q-separator dark />

        <q-card-actions>
          <q-btn padding="lg" outline>Action 1</q-btn>
          <q-btn padding="none" outline>Action 2</q-btn>
        </q-card-actions>
      </q-card>
    </section>
  </q-page>
</template>

<script setup></script>

<style lang="scss" scoped></style>
