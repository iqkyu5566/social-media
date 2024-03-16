<script setup>
import { Head, Link } from "@inertiajs/vue3";

import GroupItem from "@/Components/app/GroupItem.vue";
import TextInput from "@/Components/TextInput.vue";
import { ref } from "vue";
import { Disclosure, DisclosureButton, DisclosurePanel } from "@headlessui/vue";

const searchKeyword = ref("");

defineProps({});
</script>

<template>
    <div
        class="px-3 bg-white rounded border py-3 h-[300px] lg:h-full overflow-hidden flex flex-col"
    >
        <div class="block lg:hidden">
            <Disclosure v-slot="{}">
                <DisclosureButton class="w-full">
                    <h2 class="text-2xl font-bold mb-4">My Groups</h2>
                </DisclosureButton>
                <DisclosurePanel static>
                    <TextInput
                        :model-value="searchKeyword"
                        placeholder="Type to search"
                        class="w-full"
                    />
                    <div class="mt-3 flex-1 overflow-auto">
                        <div
                            v-if="false"
                            class="text-gray-400 flex text-center py-8"
                        >
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
                </DisclosurePanel>
            </Disclosure>
        </div>
        <div class="block lg:block">
            <Disclosure v-slot="{}">
                <DisclosureButton>
                    <h2 class="text-2xl font-bold mb-4">My Groups</h2>
                </DisclosureButton>
                <DisclosurePanel static>
                    <TextInput
                        :model-value="searchKeyword"
                        placeholder="Type to search"
                        class="w-full"
                    />
                    <div class="mt-3 flex-1 overflow-auto">
                        <div
                            v-if="false"
                            class="text-gray-400 flex text-center py-8"
                        >
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
                </DisclosurePanel>
            </Disclosure>
        </div>
    </div>
</template>

<style></style>
