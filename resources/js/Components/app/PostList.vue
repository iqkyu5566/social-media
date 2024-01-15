<script setup>
import PostItem from "@/Components/app/PostItem.vue";

const post1 = {
    user: {
        id: 1,
        avatar: "https://randomuser.me/api/portraits/women/1.jpg",
        name: "John Smith",
    },
    group: null,
    body: `
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae suscipit id laborum ratione! Dolorem exercitationem iusto maxime minima nemo voluptatibus eos corporis numquam minus sunt nisi, dicta impedit consequatur voluptate.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae suscipit id laborum ratione! Dolorem exercitationem iusto maxime minima nemo voluptatibus eos corporis numquam minus sunt nisi, dicta impedit consequatur voluptate.</p>
    `,
    created_at: "2022-01-01 15:12",
};
</script>

<template>
    <div>
        <PostItem :post="post1" />
    </div>
</template>

<style scoped></style>
