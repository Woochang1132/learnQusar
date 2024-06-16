<template>
  <q-page class="q-pa-xl">
    <section class="q-mb-xl">
      <div class="text-h4">Brand Colors</div>
      <q-separator class="q-my-md" />
      <div class="q-gutter-sm">
        <div class="q-pa-xs rounded-borders bg-primary text-yellow">
          primary
        </div>
        <div class="q-pa-md rounded-borders bg-secondary text-white">
          secondary
        </div>
        <div class="q-pa-md rounded-borders bg-accent">accent</div>
        <div class="q-pa-md rounded-borders bg-dark">dark</div>
        <div class="q-pa-md rounded-borders bg-positive">positive</div>
        <div class="q-pa-md rounded-borders bg-negative">negative</div>
        <div class="q-pa-md rounded-borders bg-info">info</div>
        <div class="q-pa-md rounded-borders bg-warning">warning</div>
        <div class="q-pa-md rounded-borders bg-purple-5">purple-5</div>
        <div class="q-pa-md rounded-borders bg-pink-7">pink-7</div>
        <div class="q-pa-md rounded-borders bg-error">error</div>
        <p>Variables</p>
      </div>
      <q-btn color="yellow" text-color="black" label="검정" />
    </section>
    <section class="q-mb-xl">
      <div class="text-h4">components</div>
      <q-separator class="q-my-md" />
      <q-btn color="white" text-color="black" label="Standard" />
      <q-btn color="primary" label="Primary" />
      <q-btn color="secondary" label="Secondary" />
      <q-btn color="amber" glossy label="Amber" />
      <q-btn color="brown-5" label="Brown 5" />
      <q-btn color="deep-orange" glossy label="Deep Orange" />
      <q-btn color="purple" label="Purple" />
      <q-btn color="black" label="Black" />
      <q-btn color="error" label="Error" />
    </section>
  </q-page>
</template>

<script setup></script>

<style lang="scss" scoped>
p {
  color: $red;
  background-color: $grey-5;
}
.text-error {
  color: $red;
}
.bg-error {
  background: $red;
}
</style>
