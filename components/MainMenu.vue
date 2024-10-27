<script setup lang="ts">
const items = ref(['GAMEPLAY','PROMO', 'CHARACTERS', 'ENVIRONMENTS', 'CONCEPTS'])
</script>

<template>
    <div class="flex flex-col">
        <div class="flex w-full justify-center pt-3 px-3">
            <NButton class="grow" btn="text" label="POST" />
            <NButton class="grow" btn="text" label="SHOP" />
            <NButton class="grow" btn="text" label="SUBSCRIBE" />
            <NButton class="grow" btn="text" label="COLLABORATE" />
        </div>
        <NSeparator />
        <div class="border border-base flex gap-x-15 p-3">
            <div v-for="item in items" :key="item" class="flex flex-col items-center justify-around gap-y-2">
                <NAvatar src="/img/salamander.jfif" avatar="outline-primary" size="2xl"/>
                <span class="text-primary text-10px font-bold">{{ item }}</span>
            </div>
        </div>

        <div class="grid grid-cols-3 gap-5 py-3">
            <div class="relative group cursor-pointer">
                <img src="/img/dragon.jfif" />
                <div class="absolute inset-0 bg-gradient-to-t from-red to-transparent opacity-0 group-hover:opacity-30 transition-opacity duration-300"/>
            </div>
            <div class="relative group cursor-pointer">
                <img src="/img/snake.jfif" />
                <div class="absolute inset-0 bg-gradient-to-t from-blue to-transparent opacity-0 group-hover:opacity-30 transition-opacity duration-300"/>
            </div>
            <div class="relative group cursor-pointer">
                <img src="/img/wolf.jfif" />
                <div class="absolute inset-0 bg-gradient-to-t from-green to-transparent opacity-0 group-hover:opacity-30 transition-opacity duration-300"/>
            </div>
        </div>
    </div>
</template>