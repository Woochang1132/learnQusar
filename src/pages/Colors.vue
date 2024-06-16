<template>
  <q-page class="q-pa-xl">
    <section class="q-mb-xl">
      <div class="text-h4">Brand Colors</div>
      <q-separator class="q-my-md" />
      <div class="q-gutter-sm">
        <div class="q-pa-xs rounded-borders bg-primary text-yellow">
          primary
        </div>
        <div class="bg-secondary">secondary</div>
        <div class="bg-accent">accent</div>
        <div class="bg-dark">dark</div>
        <div class="bg-positive">positive</div>
        <div class="bg-negative">negative</div>
        <div class="bg-info">info</div>
        <div class="bg-warning">warning</div>
        <div class="bg-purple-5">purple-5</div>
        <div class="bg-pink-7">pink-7</div>
        <div class="bg-light-blue">light-blue</div>
        <p>Variables</p>
      </div>
      <q-btn color="yellow" text-color="black" label="검정" />
    </section>
  </q-page>
</template>

<script setup></script>

<style lang="scss" scoped>
p {
  color: $red;
  background-color: $grey-5;
}
</style>
