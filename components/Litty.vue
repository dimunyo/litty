<template>
    <div class="border border-base">
        <div class="flex gap-x-4 items-center pt-3 px-3">
            <img src="/img/hot.png" class="w-24px h-24px" />
            <span class="text-primary font-bold text-lg"> WHO'S LITTY</span>
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
                        </div>
                    </div>
                </div>

                <div class="flex">
                    <img src="/img/hot.png" class="w-24px h-24px" />
                    <NButton btn="text-primary" label="74.3K" class="text-xs" />
                </div>
            </div>
        </div>
    </div>
</template>