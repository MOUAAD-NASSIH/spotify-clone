<script setup>
import HomeCard from "@/components/HomeCard.vue";
</script>

<template>
  <div class="p-2 sm:p-8">
    <button
      type="button"
      class="text-white hover:underline font-bold text-lg sm:text-2xl md:text-3xl cursor-pointer"
    >
      Podcasts to Make You Smarter
    </button>
    <div class="py-1 5"></div>
    <div class="flex item-center ">
      <HomeCard image="https://picsum.photos/id/30/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden sm:block" image="https://picsum.photos/id/49/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden md:block" image="https://picsum.photos/id/52/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden lg:block" image="https://picsum.photos/id/63/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden xl:block" image="https://picsum.photos/id/100/300/300" title="My Title Here" subTitle="my subtitle here"/>
    </div>
  </div>
  <div class="p-2 sm:p-8">
    <button
      type="button"
      class="text-white hover:underline font-bold text-lg sm:text-2xl md:text-3xl cursor-pointer"
    >
      Recommended Radio
    </button>
    <div class="py-1 5"></div>
    <div class="flex item-center ">
      <HomeCard image="https://picsum.photos/id/83/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden sm:block" image="https://picsum.photos/id/12/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden md:block" image="https://picsum.photos/id/45/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden lg:block" image="https://picsum.photos/id/67/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden xl:block" image="https://picsum.photos/id/27/300/300" title="My Title Here" subTitle="my subtitle here"/>
    </div>
  </div>
  <div class="p-2 sm:p-8">
    <button
      type="button"
      class="text-white hover:underline font-bold text-lg sm:text-2xl md:text-3xl cursor-pointer"
    >
      Recommended Songs
    </button>
    <div class="py-1 5"></div>
    <div class="flex item-center ">
      <HomeCard image="https://picsum.photos/id/10/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden sm:block" image="https://picsum.photos/id/54/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden md:block" image="https://picsum.photos/id/89/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden lg:block" image="https://picsum.photos/id/12/300/300" title="My Title Here" subTitle="my subtitle here"/>
      <HomeCard class="hidden xl:block" image="https://picsum.photos/id/33/300/300" title="My Title Here" subTitle="my subtitle here"/>
    </div>
  </div>
</template>
