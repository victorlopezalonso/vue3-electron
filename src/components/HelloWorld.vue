<template>
  <div class="hero min-h-screen">
    <div class="hero-overlay bg-opacity-60"></div>
    <div class="text-center hero-content text-neutral-content">
      <div class="max-wd-md">
        <img class="mx-auto" alt="Vue logo" src="@/assets/logo.png" />
        <h1 class="mb-5 text-5xl font-bold">{{ title }}</h1>
        <p class="mb-5 text-2xl">{{ msg }}</p>
        <a href="/components/modal#my-modal" class="btn btn-primary">
          open modal
        </a>
      </div>
    </div>
  </div>
  <div id="my-modal" class="modal">
    <div class="modal-box">
      <p>Hey There!</p>
      <div class="modal-action">
        <a href="/components/modal#" class="btn btn-primary">Accept</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    msg: String,
  },
};
</script>
