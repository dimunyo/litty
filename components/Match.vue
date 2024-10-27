<template>
    <div class="border border-base">
        <div class="flex gap-x-4 items-center justify-center w-full pt-3 px-3">
            <span class="font-bold text-lg"> MATCH</span>
        </div>
        <NSeparator />
        <div class="flex flex-col w-full">
            <div v-for="index in 5" :key="index" class="flex items-center justify-between hover:bg-muted p-3">
                <div class="flex gap-x-2 items-center">
                    <NAvatar size="16px" src="/img/avatar.png" class="object-cover" />
                    <div class="flex flex-col gap-y-2">
                        <span class="text-primary text-sm">@JOHN.DOE</span>
                        <div class="flex gap-x-2">
                            <NBadge label="GAMING" size="10px" class="rounded-full" />
                            <NBadge label="TECH" size="10px" class="rounded-full" />
                            <NBadge label="MUSIC" size="10px" class="rounded-full" />

                        </div>
                    </div>
                </div>

                <div class="flex gap-x-2">
                    <NButton btn="soft-primary square" icon label="i-lucide-x"  class="rounded-full"/>
                    <NButton btn="soft-primary square" icon label="i-lucide-heart"  class="rounded-full"/>

                </div>
            </div>
        </div>
    </div>
</template>