<script setup>
import { Head, Link } from "@inertiajs/vue3";

import GroupList from "@/Components/app/GroupList.vue";
import FollowingList from "@/Components/app/FollowingList.vue";
import CreatePost from "@/Components/app/CreatePost.vue";
import PostList from "@/Components/app/PostList.vue";

defineProps({});
</script>

<template>
    <Head title="Social Media App" />

    <div class="grid lg:grid-cols-12 gap-3 p-4 h-full">
        <div class="lg:col-span-3 lg:order-1 h-full overflow-hidden">
            <GroupList />
        </div>
        <div class="lg:col-span-3 lg:order-3 h-full overflow-auto">
            <FollowingList />
        </div>
        <div class="lg:col-span-6 lg:order-2 h-full">
            <CreatePost />
            <PostList />
        </div>
    </div>
</template>

<style></style>
