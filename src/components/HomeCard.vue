<script setup>
import { toRefs } from "vue";
import { RouterLink } from "vue-router";

const props = defineProps({
  image: String,
  title: String,
  subTitle: String,
});
const {image, title, subTitle} = toRefs(props);
</script>

<template>
    <RouterLink to="/library">
        <div class="rounded-md bg-[#111111] hover:bg-[#3f3d3d] p-1 sm:p-4 m-1 sm:m-2 cursor-pointer">
            <img class="rounded-md" :src="image">
            <div class="text-white pt-4 font-semibold text-[17px]">{{ title }}</div>
            <div class="text-gray-400 pt-1 pb-3 text-[14px]">{{ subTitle }}</div>
        </div>
    </RouterLink>
</template>
