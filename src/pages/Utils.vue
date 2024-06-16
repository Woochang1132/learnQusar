<template>
  <div class="q-pa-md">
    <div class="q-gutter-sm">
      <div>
        <q-checkbox v-model="right" label="Label on Right" />
      </div>

      <div>
        <q-checkbox left-label v-model="left" label="Label on Left" />
      </div>

      <div>
        <q-checkbox
          v-model="right2"
          label="Swipe"
          checked-icon="swipe_left"
          unchecked-icon="swipe_right"
          color="green"
          keep-color
        />
      </div>

      <div>
        <q-checkbox
          left-label
          v-model="left2"
          label="I agree"
          checked-icon="task_alt"
          unchecked-icon="highlight_off"
        />
      </div>
    </div>
  </div>

  <div class="q-pa-md q-gutter-sm">
    <q-banner class="bg-primary text-white">
      Unfortunately, the credit card did not go through, please try again.
      <template v-slot:action>
        <q-btn flat color="white" label="Dismiss" />
        <q-btn flat color="white" label="Update Credit Card" />
      </template>
    </q-banner>

    <q-banner :class="$q.dark.isActive ? 'bg-grey-9' : 'bg-grey-3'">
      <template v-slot:avatar>
        <q-icon name="signal_wifi_off" color="primary" />
      </template>
      You have lost connection to the internet. This app is offline.
      <template v-slot:action>
        <q-btn flat color="primary" label="Turn on Wifi" />
      </template>
    </q-banner>

    <q-banner inline-actions class="text-white bg-red">
      You have lost connection to the internet. This app is offline.
      <template v-slot:action>
        <q-btn flat color="white" label="Turn ON Wifi" />
      </template>
    </q-banner>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
