<template>
    <div class="border border-base">
        <div class="flex gap-x-4 items-center justify-center w-full pt-3 px-3">
            <span class="font-bold text-lg"> TRENDS</span>
        </div>
        <NSeparator />
        <div class="flex flex-col w-full">
            <div v-for="index in 5" :key="index" class="flex items-center justify-between hover:bg-muted p-3">
                <div class="flex gap-x-2 items-center justify-between w-full">
                    <NBadge label="GAMING" size="10px" class="rounded-full" />
                    <div class="flex flex-col items-center">
                        <span class="text-10px">POSTS</span>
                        <span class="text-10px">123K</span>
                    </div>
                    <div>
                        <NAvatarGroup :max="2" size="xs">
                            <NAvatar src="/img/avatar.png" />
                            <NAvatar src="img/profile.jfif" />
                            <NAvatar src="img/records.jfif" />
                        </NAvatarGroup>
                    </div>

                    <div class="flex items-center">
                        <img src="/img/hot.png" class="w-24px h-24px" />
                        <NButton btn="text-primary" label="121.1M" class="text-xs" />
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>