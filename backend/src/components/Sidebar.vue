<template>
    <div class="w-[200px] bg-indigo-700 py-4 px-2 text-white">
        <router-link
            :to="{ name: 'app.dashboard' }"
            class="flex items-center py-2 px-2 rounded hover:bg-black/30 transition-colors mb-2"
        >
            <span class="mr-2"><HomeIcon class="w-5" /></span>
            <span class="text-md">Dashboard</span>
        </router-link>

        <router-link
            :to="{ name: 'app.dashboard' }"
            class="flex items-center py-2 px-2 rounded hover:bg-black/30 transition-colors mb-2"
        >
            <span class="mr-2"><ClipboardIcon class="w-5" /></span>
            <span class="text-md">Products</span>
        </router-link>

        <router-link
            :to="{ name: 'app.dashboard' }"
            class="flex items-center py-2 px-2 rounded hover:bg-black/30 transition-colors mb-2"
        >
            <span class="mr-2"><UserIcon class="w-5" /></span>
            <span class="text-md">Users</span>
        </router-link>

        <router-link
            :to="{ name: 'app.dashboard' }"
            class="flex items-center py-2 px-2 rounded hover:bg-black/30 transition-colors mb-2"
        >
            <span class="mr-2"><ChartBarIcon class="w-5" /></span>
            <span class="text-md">Reports</span>
        </router-link>
    </div>
</template>

<script setup>
import {
    HomeIcon,
    UserIcon,
    ClipboardIcon,
    ChartBarIcon,
} from "@heroicons/vue/24/outline";
</script>
