<script setup lang="ts">
definePageMeta({
  colorMode: 'dark',
})
</script>

<template>
    <div class="mt-14 grid grid-cols-8 gap-5 p-2">
        <Litty class="col-span-2" />
        <Profile  class="col-span-4"/>
        <Match class="col-span-2" />
        <div class="col-span-2">
            <Trends />
        </div>
        <MainMenu class="col-span-4" />
        <div class="col-span-2">
            <Events />
        </div>
    </div>
</template>