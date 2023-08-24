<script setup>
    import CategorySelect from "@/components/CategorySelect.vue"
</script>

<template>
    <div class="p-6 sm:p-8">
        <div class="text-white font-semibold pb-6 text-lg sm:text-2xl md:text-3xl">
            Browse all
        </div>
        <div class="py-1 5"></div>
        <div class="grid gap-3 lg:gap-6 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 xl:grid-cols-6">
            <CategorySelect category="Podcasts" image="https://picsum.photos/id/11/300/300" />
            <CategorySelect category="Live Events" image="https://picsum.photos/id/12/300/300" />
            <CategorySelect category="Made For You" image="https://picsum.photos/id/13/300/300" />
            <CategorySelect category="New release" image="https://picsum.photos/id/33/300/300" />
            <CategorySelect category="Ramadan" image="https://picsum.photos/id/95/300/300" />
            <CategorySelect category="Pop" image="https://picsum.photos/id/65/300/300" />
            <CategorySelect category="Hip-Hop" image="https://picsum.photos/id/21/300/300" />
            <CategorySelect category="Arab" image="https://picsum.photos/id/100/300/300" />
            <CategorySelect category="Charts" image="https://picsum.photos/id/23/300/300" />
            <CategorySelect category="Afro" image="https://picsum.photos/id/24/300/300" />
            <CategorySelect category="Rock" image="https://picsum.photos/id/41/300/300" />
            <CategorySelect category="Latin" image="https://picsum.photos/id/42/300/300" />
            <CategorySelect category="Discover" image="https://picsum.photos/id/51/300/300" />
            <CategorySelect category="Mood" image="https://picsum.photos/id/52/300/300" />
            <CategorySelect category="Workout" image="https://picsum.photos/id/53/300/300" />
            <CategorySelect category="R&B" image="https://picsum.photos/id/68/300/300" />
            <CategorySelect category="At Home" image="https://picsum.photos/id/47/300/300" />
            <CategorySelect category="Love" image="https://picsum.photos/id/16/300/300" />
            <CategorySelect category="Gaming" image="https://picsum.photos/id/85/300/300" />
        </div>
    </div>
</template>
