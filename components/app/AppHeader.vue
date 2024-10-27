<template>
    <div class="min-h-12 flex items-center justify-between gap-x-2 px-5 py-2 w-60%">
        <div class="flex items-center gap-4">
            <img src="/img/logo.png" class="w-32px h-32px" />
            <NInput
            leading="i-heroicons-magnifying-glass-20-solid"
            placeholder="Search"
            />
        </div>
        <div class="flex items-center gap-2">
            <NButton btn="text square" icon label="i-lucide-file-plus" />
            <NButton btn="text square" icon label="i-lucide-compass" />
            <NIndicator indicator="solid-red" label="4">
                <NButton btn="text square" icon label="i-lucide-mail" />
            </NIndicator>
            <NIndicator indicator="solid-red" label="16">
                <NButton btn="text square" icon label="i-lucide-message-square-warning" />
            </NIndicator>
            <NButton btn="text square" icon label="i-lucide-house" />
            <NAvatar avatar="outline-indigo" src="/img/records.jfif" class="w-32px h-32px" />
        </div>
    </div>
</template>