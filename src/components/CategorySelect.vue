<script setup>
    import {ref, toRefs} from "vue"
    import {RouterLink} from "vue-router"
    import uniqolor from "uniqolor";

    const randColor = ref("")
    randColor.value = uniqolor.random()

    const props = defineProps({
        category: String,
        image: String,
    })
    const {category, image} = toRefs(props)
</script>

<template>
    <RouterLink to="/library">
        <div
            v-if="randColor.color"
            class="contrast-[2] brightness-[0.87] rounded-xl aspect-square relative overflow-hidden"
            :style="`background-color: ${randColor.color}`"
        >
            <div class="text-white drop-shadow-lg pt-3 pl-4 font-semibold text-[23px]"> {{ category }} </div>
            <img class="absolute contrast-[0.55] -right-3.5 bottom-0 max-w-[100px] sm:max-w-[70px] rotate-[20deg] z-[-1]" :src="image || ''" alt="">
        </div>
    </RouterLink>
</template>

