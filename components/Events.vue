<template>
    <div class="border border-base space-y-5">
        <div class="flex gap-x-4 items-center justify-center w-full pt-3 px-3">
            <span class="font-bold text-lg"> EVENTS</span>
        </div>

        <div class="flex flex-col w-full border-y border-primary">
            <div class="flex w-full hover:bg-muted items-center p-3 gap-x-2">
                <img src="/img/event1.jfif" class="min-w-129px h-76px object-cover" />
                <div class="w-full">
                    <div class="flex justify-between items-center">
                        <p class="text-primary text-xs font-bold tracking-widest">NIKE PENTHOUSE PARTY</p>
                        <div>
                            <NBadge label="GAMING" size="10px" class="rounded-full" />
                        </div>
                    </div>
                    <span class="text-sm">Manchester, United Kingdom</span>
                    <div class="flex justify-between items-center w-50% mt-5">
                        <span class="text-xs text-muted">GAIN</span>
                        <div class="flex">
                            <img src="/img/hot.png" class="w-20px h-20px" />
                            <NButton btn="text-primary" label="50K" class="text-xs" />
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="flex flex-col w-full border-y border-primary">
            <div class="flex w-full hover:bg-muted items-center p-3 gap-x-2">
                <img src="/img/event2.jfif" class="min-w-129px h-76px object-cover" />
                <div class="w-full">
                    <div class="flex justify-between items-center">
                        <p class="text-primary text-xs font-bold tracking-widest">TWITCH VR PARTY</p>
                        <div>
                            <NBadge label="GIVEAWAY" size="10px" class="rounded-full" />
                        </div>
                    </div>
                    <span class="text-sm">VIRTUAL</span>
                    <div class="flex justify-between items-center w-50% mt-5">
                        <span class="text-xs text-muted">REQUIRED</span>
                        <div class="flex">
                            <img src="/img/hot.png" class="w-20px h-20px" />
                            <NButton btn="text-primary" label="50K" class="text-xs" />
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="flex flex-col w-full border-y border-primary">
            <div class="flex w-full hover:bg-muted items-center p-3 gap-x-2">
                <img src="/img/event3.jfif" class="min-w-129px h-76px object-cover" />
                <div class="w-full">
                    <div class="flex justify-between items-center">
                        <p class="text-primary text-xs font-bold tracking-widest">RSVP MANSION PARTY</p>
                        <div>
                            <NBadge label="SPECIAL" size="10px" class="rounded-full" />
                        </div>
                    </div>
                    <span class="text-sm">Manchester, United Kingdom</span>
                    <div class="flex justify-between items-center w-50% mt-5">
                        <span class="text-xs text-muted">COST</span>
                        <div class="flex">
                            <NButton btn="text-primary" label="50K" leading="i-lucide-euro" class="text-xs" />
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>