<template>
    <div class="flex flex-col relative">
        <NAvatar src="/img/profile.jfif" class="absolute left-10 top-45" size="64px"/>
        <img src="/img/hero.png" class="h-256px object-cover" />
        <div class="flex flex-col w-75% ml-auto gap-y-2">
            <div class="flex items-center justify-between">
                <div>
                    <div class="flex">
                        <h1 class="font-bold text-24px">Spawn World</h1>
                        <NButton icon label="i-lucide-settings" btn="text square" />
                    </div>
                    <span class="text-primary">@spawn.world</span>
                </div>

                <div class="flex gap-4">
                    <NButton label="message" size="xs" />
                    <NButton label="follow" size="xs" />
                    <NButton icon label="i-lucide-ellipsis" btn="text square" />
                </div>
            </div>

            <div class="flex flex-col justify-center items-center">
                <p class="text-muted leading-relaxed text-center">Creating a new MMORPG which features fast paced action
                    combat <br>
                    And a world that evolves around the player base <span class="text-primary">#Spawn</span>
                </p>
                <span class="text-primary font-bold text-sm">SPAWN.WORLD</span>
            </div>

        </div>
        
        <div class="flex w-full justify-between mt-5">
            <NButton btn="~" label="60 POSTS" />
            <NButton btn="~" label="5 PRODUCTS" />
            <NButton btn="~" label="12.2K FOLLOWERS" />
            <div class="flex">
                <img src="/img/hot.png" class="w-32px h-32px" />
                <NButton btn="text-primary" label="74.3K" />
            </div>
        </div>

    </div>
</template>