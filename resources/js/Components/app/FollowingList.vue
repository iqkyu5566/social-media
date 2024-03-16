<script setup>
import { Head, Link } from "@inertiajs/vue3";

import TextInput from "@/Components/TextInput.vue";
import { ref } from "vue";
import FollowingItem from "@/Components/app/FollowingItem.vue";

const searchKeyword = ref("");

defineProps({});
</script>

<template>
    <div class="px-3 bg-white rounded border py-3">
        <h2 class="text-2xl font-bold mb-4">My Followings</h2>
        <TextInput
            :model-value="searchKeyword"
            placeholder="Type to search"
            class="w-full"
        />
        <div class="py-8">
            <div v-if="false" class="text-gray-400 flex text-center py-8">
                You don't have Friends yet
            </div>
            <div v-else>
                <FollowingItem
                    image="https://picsum.photos/100"
                    title="John Doe"
                />
                <FollowingItem
                    image="https://picsum.photos/100"
                    title="Elon Musk"
                />
            </div>
        </div>
    </div>
</template>

<style></style>
