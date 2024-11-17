<template>
    <div>
        <h1 class="text-white text-5xl font-bold text-center">Frequently Asked <span
                class="text-[#00ADB5]">Questions</span></h1>
        <div class="mt-10 max-w-[850px] mx-auto">
            <div v-for="(item, index) in Questions" :key="item.id"
                class="p-7 bg-[#f9f9fc0c] rounded-sm flex-col items-start gap-y-2.5 flex border border-[#00acb50c]">
                <div class="flex justify-between w-full">
                    <h4 class="text-lg text-white font-bold">{{ item.title }}</h4>
                    <button @click="openStates[index] = !openStates[index]"><img src="/img/Frame 52.svg"
                            alt=""></button>
                </div>

                <p v-if="openStates[index]" class="text-sm text-[#999999]">{{ item.description }}</p>
            </div>
        </div>
    </div>
</template>


<script setup>
import { ref } from 'vue';


const Questions = ([
    {
        id: 1,
        title: 'Add commonly asked questions here',
        description: ' Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc. Sollicitudin nulla ut quis in vestibulum nunc nunc eget. Est nulla fringilla nisl quis morbi. Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc.'
    },
    {
        id: 2,
        title: 'Add commonly asked questions here',
        description: ' Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc. Sollicitudin nulla ut quis in vestibulum nunc nunc eget. Est nulla fringilla nisl quis morbi. Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc.'
    },
    {
        id: 3,
        title: 'Add commonly asked questions here',
        description: ' Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc. Sollicitudin nulla ut quis in vestibulum nunc nunc eget. Est nulla fringilla nisl quis morbi. Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc.'
    },
    {
        id: 4,
        title: 'Add commonly asked questions here',
        description: ' Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc. Sollicitudin nulla ut quis in vestibulum nunc nunc eget. Est nulla fringilla nisl quis morbi. Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc.'
    },
    {
        id: 5,
        title: 'Add commonly asked questions here',
        description: ' Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc. Sollicitudin nulla ut quis in vestibulum nunc nunc eget. Est nulla fringilla nisl quis morbi. Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc.'
    },
    {
        id: 6,
        title: 'Add commonly asked questions here',
        description: ' Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc. Sollicitudin nulla ut quis in vestibulum nunc nunc eget. Est nulla fringilla nisl quis morbi. Lorem ipsum dolor sit amet consectetur. Quis elementum libero purus auctor nec viverra nunc.'
    },
])

const openStates = ref(Questions.map(() => false));
</script>
