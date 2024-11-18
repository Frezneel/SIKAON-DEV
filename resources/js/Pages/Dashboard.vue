<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2
                class="text-xl font-semibold leading-tight text-gray-800"
            >
                Dashboard
            </h2>
        </template>

        <div class="py-12">
            <div class="mx-auto max-w-7xl sm:px-6 lg:px-8">
                <div class="overflow-hidden bg-white shadow-sm sm:rounded-lg">
                    <div class="p-6 text-gray-900">
                        You're logged in!
                    </div>
                    <div class="p-6 text-center text-xl font-extrabold text-gray-900">
                        Menu
                    </div>
                    <div class="grid grid-cols-4 gap-4 mb-5 p-2">
                        <button class="border bg-white space-y-3 p-4 rounded-lg shadow ">
                            <div class="flex items-center space-x-2 text-sm">
                                <div>
                                    <a href="#" class="text-blue-500 font-bold">#1</a>
                                </div>
                                <div class="text-gray-500">17-11-2024</div>
                                <div class="text-gray-500">
                                    <span class="p-1.5 text-xs font-medium uppercase track-wider text-yellow-800 bg-yellow-200 rounded-lg">
                                        checking
                                    </span>
                                </div>
                            </div>
                            <div class="text-sm text-gray-700 text-left">
                                SIKA Request
                            </div>
                        </button>
                        <div class="border bg-white space-y-3 p-4 rounded-lg shadow ">
                            <div class="flex items-center space-x-2 text-sm">
                                <div>
                                    <a href="#" class="text-blue-500 font-bold">#1</a>
                                </div>
                                <div class="text-gray-500">17-11-2024</div>
                                <div class="text-gray-500">
                                    <span class="p-1.5 text-xs font-medium uppercase track-wider text-yellow-800 bg-yellow-200 rounded-lg">
                                        checking
                                    </span>
                                </div>
                            </div>
                            <div class="text-sm text-gray-700">
                                Galih Test
                            </div>
                        </div>
                        <div class="border bg-white space-y-3 p-4 rounded-lg shadow ">
                            <div class="flex items-center space-x-2 text-sm">
                                <div>
                                    <a href="#" class="text-blue-500 font-bold">#1</a>
                                </div>
                                <div class="text-gray-500">17-11-2024</div>
                                <div class="text-gray-500">
                                    <span class="p-1.5 text-xs font-medium uppercase track-wider text-yellow-800 bg-yellow-200 rounded-lg">
                                        checking
                                    </span>
                                </div>
                            </div>
                            <div class="text-sm text-gray-700">
                                
                            </div>
                        </div>

                    </div>
                    
                    <div class="grid justify-items-center mb-3 text-xl font-bold">
                        SIKA REQUEST
                    </div>
                    <div class="m-5 rounded-lg shadow-lg bg-gray-300 overflow-auto">
                        <table class="w-full table-auto">
                            <thead class="bg-gray-300 border-b-2 border-gray-200">
                                <tr>
                                    <th class="p-3 text-sm font-semibold tracking-wide text-left">No</th>
                                    <th class="p-3 text-sm font-semibold tracking-wide text-left">Name</th>
                                    <th class="p-3 text-sm font-semibold tracking-wide text-left">Status</th>
                                    <th class="p-3 text-sm font-semibold tracking-wide text-left">Action</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="bg-white text-sm">
                                    <td class="p-3 text-left">1</td>
                                    <td class="p-3 text-left">Galih Test</td>
                                    <td class="p-3 text-left">
                                        <span class="p-1.5 text-xs font-medium uppercase tracking-wider text-yellow-800 bg-yellow-200 rounded-lg">Checking</span>
                                    </td>
                                    <td class="p-3 text-left">
                                        <button class="button bg-orange-400 m-2">Edit</button>
                                        <button class="bg-white m-2">Delete</button>
                                    </td>
                                </tr>
                                <tr class="bg-gray-100 text-sm">
                                    <td class="p-3 text-left">2</td>
                                    <td class="p-3 text-left">User Test</td>
                                    <td class="p-3 text-left">
                                        <span class="p-1.5 text-xs font-medium uppercase tracking-wider text-green-800 bg-green-200 rounded-lg">Success</span>
                                    </td>
                                    <td class="p-3 text-left">
                                        <button class="button bg-orange-400 m-2">Edit</button>
                                        <button class="bg-white m-2">Delete</button>
                                    </td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </AuthenticatedLayout>
</template>
