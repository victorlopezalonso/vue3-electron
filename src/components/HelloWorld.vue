<template>
  <div class="container mt-10 mx-auto">
    <div class="box-border rounded-full border-2 border-green-500 p-8">
      <img class="mx-auto" alt="Vue logo" src="@/assets/logo.png" />
      <p class="text-center text-3xl font-medium">{{ msg }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    msg: String,
  },
};
</script>
