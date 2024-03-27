<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div px-20 pt-30>
    <p>
      <a
        rel="noreferrer" href="https://github.com/antfu/vitesse-lite" target="_blank"
        text-8xl color-stone-800 font-bold font-allura
      >
        Shane Hwang
      </a>
    </p>
    <div flex flex-col gap-2 pt-8 text-xl color-stone-800>
      Front-end developer / Amateur designer.
      <div />
      <div>
        Currently studying at Nuist.
      </div>
      <div>
        I like making interesting projects.
      </div>
    </div>

    <div py-8 />
  </div>

  <div w-full flex flex-col items-center justify-center gap-15>
    <div flex items-center justify-center gap-18>
      <a href="#" class="flex flex-col items-center border border-gray-200 rounded-lg bg-white shadow shadow-xl md:max-w-md md:flex-row hover:bg-gray-100">
        <img class="h-48 w-full rounded-t-lg object-cover md:w-48 md:rounded-none md:rounded-s-lg" alt="" src="https://images.unsplash.com/photo-1710874087896-6683c258deb4?w=400&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxNHx8fGVufDB8fHx8fA%3D%3D">
        <div class="flex flex-col justify-between p-4 leading-normal">
          <h5 class="mb-2 text-2xl text-gray-900 font-bold tracking-tight">Project One</h5>
          <p class="mb-3 text-gray-700 font-normal dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
        </div>
      </a>
      <a href="#" class="flex flex-col items-center border border-gray-200 rounded-lg bg-white shadow shadow-xl md:max-w-md md:flex-row hover:bg-gray-100">
        <img class="h-48 w-full rounded-t-lg object-cover md:w-48 md:rounded-none md:rounded-s-lg" alt="" src="https://images.unsplash.com/photo-1711319551857-9108cbd44e71?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwyNHx8fGVufDB8fHx8fA%3D%3D">
        <div class="flex flex-col justify-between p-4 leading-normal">
          <h5 class="mb-2 text-2xl text-gray-900 font-bold tracking-tight">Project Two</h5>
          <p class="mb-3 text-gray-700 font-normal dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
        </div>
      </a>
    </div>

    <div flex items-center justify-center gap-18>
      <a href="#" class="flex flex-col items-center border border-gray-200 rounded-lg bg-white shadow shadow-xl md:max-w-md md:flex-row hover:bg-gray-100">
        <img class="h-48 w-full rounded-t-lg object-cover md:w-48 md:rounded-none md:rounded-s-lg" alt="" src="https://images.unsplash.com/photo-1682687220945-922198770e60?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHw1Nnx8fGVufDB8fHx8fA%3D%3D">
        <div class="flex flex-col justify-between p-4 leading-normal">
          <h5 class="mb-2 text-2xl text-gray-900 font-bold tracking-tight">Project Three</h5>
          <p class="mb-3 text-gray-700 font-normal dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
        </div>
      </a>
      <a href="#" class="flex flex-col items-center border border-gray-200 rounded-lg bg-white shadow shadow-xl md:max-w-md md:flex-row hover:bg-gray-100">
        <img class="h-48 w-full rounded-t-lg object-cover md:w-48 md:rounded-none md:rounded-s-lg" alt="" src="https://images.unsplash.com/photo-1711319551829-3fadadf67cd9?q=80&w=2629&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
        <div class="flex flex-col justify-between p-4 leading-normal">
          <h5 class="mb-2 text-2xl text-gray-900 font-bold tracking-tight">Project Four</h5>
          <p class="mb-3 text-gray-700 font-normal dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
        </div>
      </a>
    </div>
  </div>

  <!-- footer -->
  <!-- bottom footer fixed -->
  <div class="fixed bottom-0 w-full bg-gray-800 text-white">
    <div class="mx-auto px-8 py-4 container">
      <div class="flex flex-wrap justify-center">
        <div class="w-full text-center lg:w-1/2 lg:text-left">
          <p class="text-sm text-white font-bold">
            © 2024 Shane Hwang. All rights reserved.
          </p>
        </div>
        <div class="w-full text-center lg:w-1/2 lg:text-right">
          <a href="#" class="px-3 text-white hover:text-gray-200">Terms of Service</a>
          <a href="#" class="px-3 text-white hover:text-gray-200">Privacy Policy</a>
        </div>
      </div>
    </div>
  </div>
  <!-- end footer -->
</template>

<style>
body {
  /* background image */
  background-image: url('/sea.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
</style>
