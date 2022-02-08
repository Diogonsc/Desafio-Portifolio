<template>
  <div class="q-pa-md q-gutter-sm">
    <q-btn
      class="botao"
      no-caps
      :color="color"
      :text-color="text"
      :style="style"
      :label="label"
      :icon-right="icon"
    ></q-btn>
  </div>
</template>

<script>
export default {
  props: {
    class: String,
    label: String,
    color: String,
    text: String,
    style: String,
    icon: String,
  },
};
</script>

<style></style>
