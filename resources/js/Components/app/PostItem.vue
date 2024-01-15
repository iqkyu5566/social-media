<script>
export default {
    setup() {
        return {};
    },
};
</script>

<template>
    <div>
        <div>
            <img :src="post.user.avatar" />
            <h4>{{ post.user.name }}</h4>
        </div>
        <div v-html="post.body"></div>
    </div>
</template>

<style lang="scss" scoped></style>
