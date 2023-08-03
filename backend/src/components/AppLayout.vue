<template>
    <div class="flex min-h-full bg-gray-100">
        <!-- Sidebar -->
        <Sidebar />
        <div class="flex-1">
            <TopHeader />
            <main class="p-6">
                <div class="p-4 rounded bg-white">
                    <router-view></router-view>
                </div>
            </main>
        </div>
    </div>
</template>

<script setup>
import Sidebar from "./Sidebar.vue";
import TopHeader from "./TopHeader.vue";
</script>
