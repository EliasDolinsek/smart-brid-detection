<template>
  <div>
    <div :style="{backgroundImage: `url(${backgroundImage})` }"
         class="bg-cover bg-center bg-no-repeat w-screen h-screen" />
    <div class="absolute bottom-0 left-0 mb-12 ml-12">
      <router-link to="/overview" class="flex items-center gap-2 text-purple-700 font-semibold antialiased">START APP <IconArrowRight /></router-link>
      <h1 class="text-2xl font-light">Smart Bird Detection</h1>
      <p class="font-light">Over the last <span class="italic font-normal">234 days 104 birds</span> were detected</p>
      <div class="flex gap-6 mt-3">
        <BirdCard title="TODO" subtitle="Test"
                  image-url="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.DkbpxbixoK0gfNAjgtXauQHaHP%26pid%3DApi&f=1&ipt=864e62026de8bea66780b46ff2378eff3e43cd6cdc58b530cd5744e0d08e0e54&ipo=images"/>
        <BirdCard title="TODO" subtitle="Test"
                  image-url="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.DkbpxbixoK0gfNAjgtXauQHaHP%26pid%3DApi&f=1&ipt=864e62026de8bea66780b46ff2378eff3e43cd6cdc58b530cd5744e0d08e0e54&ipo=images"/>
      </div>
    </div>
  </div>
</template>

<script setup>
import backgroundImage from "~/assets/background.svg"
</script>