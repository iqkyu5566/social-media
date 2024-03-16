<script setup>
import PostItem from "@/Components/app/PostItem.vue";

const post1 = {
    user: {
        id: 1,
        avatar: "https://randomuser.me/api/portraits/men/35.jpg",
        name: "John Smith",
    },
    group: null,
    attachments: [
        {
            id: 1,
            name: "test.png",
            url: "https://picsum.photos/1000",
            mime: "image/png",
        },
        {
            id: 2,
            name: "test2.png",
            url: "https://picsum.photos/1000",
            mime: "image/png",
        },
        {
            id: 3,
            name: "MyDoc.docx",
            url: "https://test.docx",
            mime: "application/msword",
        },
    ],
    body: `
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae suscipit id laborum ratione! Dolorem exercitationem iusto maxime minima nemo voluptatibus eos corporis numquam minus sunt nisi, dicta impedit consequatur voluptate.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae suscipit id laborum ratione! Dolorem exercitationem iusto maxime minima nemo voluptatibus eos corporis numquam minus sunt nisi, dicta impedit consequatur voluptate.</p>
    `,
    created_at: "2022-01-01 15:12",
};
const post2 = {
    user: {
        id: 1,
        avatar: "https://randomuser.me/api/portraits/men/20.jpg",
        name: "Ilham J.E",
    },
    group: {
        id: 1,
        name: "Laravel Developer",
    },
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
        <PostItem :post="post2" />
    </div>
</template>

<style scoped></style>
