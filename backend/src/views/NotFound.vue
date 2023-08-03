<template>
    <div class="flex justify-center items-center min-h-full w-full min-w-full">
        <div class="sm:flex">
            <div
                class="text-indigo-600 self-start text-6xl px-8 font-bold border-r mt-1"
            >
                404
            </div>
            <div class="px-8 mt-1">
                <h1 class="text-5xl font-bold mb-2">Page Not Found</h1>
                <p class="text-gray-400 mb-10">
                    Please check the URL in address bar and try again
                </p>
                <div>
                    <router-link
                        :to="{ name: 'app.dashboard' }"
                        class="rounded-md bg-indigo-600 px-4 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600 py-3"
                    >
                        Go back home
                    </router-link>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup></script>
