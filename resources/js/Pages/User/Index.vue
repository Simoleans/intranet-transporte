<script setup>
import { Head } from "@inertiajs/inertia-vue3";
import AuthenticatedLayout from '@/Layouts/Authenticated.vue'
//import Table from './components/Table.vue'
//import LinkButton from "@/Components/LinkButton.vue";


const props = defineProps({
    users: Array,
});
</script>
<template>
    <Head title="Usuarios" />
    <AuthenticatedLayout>
        <div class="mx-auto px-4 sm:px-6 lg:px-8 py-12">
            <div class="bg-white p-7 rounded-md">
                <div class="w-full pb-5">
                    <div class="flex justify-between overflow-hidden shadow-sm sm:rounded-lg">
                        <h3 class="text-gray-900 text-2xl font-bold">
                            Usuarios
                        </h3>


                    </div>
                </div>
                <div class="w-full">
                    <div>

                    </div>
                </div>
            </div>
        </div>
    </AuthenticatedLayout>
</template>

