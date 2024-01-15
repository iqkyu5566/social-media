<script setup>
import { Head, Link } from "@inertiajs/vue3";

import GroupItem from "@/Components/app/GroupItem.vue";
import TextInput from "@/Components/TextInput.vue";
import { ref } from "vue";

const searchKeyword = ref("");

defineProps({});
</script>

<template>
    <div class="px-3">
        <h2 class="text-2xl font-bold mb-4">My Groups</h2>
        <TextInput :model-value="searchKeyword" placeholder="Type to search" />
        <div class="py-8">
            <div v-if="false" class="text-gray-400 flex text-center py-8">
                You are not in any groups
            </div>
            <div v-else>
                <GroupItem
                    image="https://picsum.photos/100"
                    title="Laravel Developer"
                    description="Lorem ipsum dolor sit amet consectetur
                                adipisicing elit. Eius, doloribus."
                />
                <GroupItem
                    image="https://picsum.photos/100"
                    title="Vue js. Developer"
                    description="Lorem ipsum dolor sit amet consectetur
                                adipisicing elit. Eius, doloribus."
                />
            </div>
        </div>
    </div>
</template>

<style></style>
