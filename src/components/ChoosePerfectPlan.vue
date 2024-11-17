<template>
    <div class="flex flex-col items-center">
        <h2 class="text-5xl font-bold text-white text-center">Choose the <span class="text-[#00ADB5]">Perfect
                Plan</span></h2>
        <div class="flex justify-center gap-x-8 mt-7">
            <div class="flex gap-x-4 p-1 border border-white text-white rounded-[40px]">
                <button @click="payment = !payment"
                    class="px-4 py-5  rounded-[40px] text-lg leading-5 font-medium duration-300"
                    :class="payment ? '' : 'bg-[#00ADB5]'">Monthly</button>
                <button @click="payment = !payment"
                    class="px-4 py-5  rounded-[40px]  text-lg leading-5 font-medium duration-300"
                    :class="payment ? 'bg-[#00ADB5]' : ''">Yearly</button>
            </div>
        </div>
        <span class="text-center text-[#999999] mt-6">Get 2 months for free by subscribing yearly!</span>
    </div>
    <div class="grid grid-cols-4 gap-10 mt-9">

        <div v-for="item in free" :key="item.id" class="text-white p-7 ">
            <span class="text-xl font-medium">{{ item.type }}</span>
            <div class="flex items-end mt-2">
                <span v-if="!payment" class="text-4xl">${{ item.price }}</span>
                <span v-else class="text-4xl">${{ item.price * 12 }}</span>
            </div>
            <p class="mt-5 max-w-[230px]">{{ item.description }}</p>
            <ul class="flex flex-col gap-y-3.5 mt-5">
                <li v-for="item in item.features" class="flex gap-x-3"><img src="/img/checkbox-circle.svg" alt="">{{
                    item.description }}</li>
            </ul>
            <button
                class="w-full mt-7 py-3.5 border border-[#00ADB5] rounded-lg text-[#00ADB5] hover:bg-[#00ADB5] hover:text-white duration-300">Choose
                Plan</button>
        </div>

        <div v-for="item in basic" :key="item.id" class="text-white p-7 ">
            <span class="text-xl font-medium">{{ item.type }}</span>
            <div class="flex items-end mt-2">
                <span v-if="!payment" class="text-4xl">${{ item.price }}</span>
                <span v-else class="text-4xl">${{ item.price * 12 }}</span>
            </div>
            <p class="mt-5 max-w-[230px]">{{ item.description }}</p>
            <ul class="flex flex-col gap-y-3.5 mt-5">
                <li v-for="item in item.features" class="flex gap-x-3"><img src="/img/checkbox-circle.svg" alt="">{{
                    item.description }}</li>
            </ul>
            <button
                class="w-full mt-7 py-3.5 border border-[#00ADB5] rounded-lg text-[#00ADB5] hover:bg-[#00ADB5] hover:text-white duration-300">Choose
                Plan</button>
        </div>

        <div v-for="item in pro" :key="item.id" class="text-white p-7 bg-[#00ADB5] rounded-2xl ">
            <span class="text-xl font-medium">{{ item.type }}</span>
            <div class="flex items-end mt-2">
                <span v-if="!payment" class="text-4xl">${{ item.price }}</span>
                <span v-else class="text-4xl">${{ item.price * 12 }}</span>
            </div>
            <p class="mt-5 max-w-[230px]">{{ item.description }}</p>
            <ul class="flex flex-col gap-y-3.5 mt-5">
                <li v-for="item in item.features" class="flex gap-x-3"><img src="/img/checkbox-circle-white.svg"
                        alt="">{{
                            item.description }}</li>
            </ul>
            <button
                class="w-full mt-7 py-3.5 border border-[#00ADB5] rounded-lg bg-white text-[#00ADB5] hover:bg-white/50 hover:text-white duration-300">Choose
                Plan</button>
        </div>

        <div v-for="item in Business" :key="item.id" class="text-white p-7 bg-white/10 rounded-2xl ">
            <span class="text-xl font-medium">{{ item.type }}</span>
            <div class="flex items-end mt-2">
                <span v-if="!payment" class="text-4xl">${{ item.price }}</span>
                <span v-else class="text-4xl">${{ item.price * 12 }}</span>
                <span class="text-[FFFFFF]">/{{ item.time }}</span>
            </div>
            <p class="mt-5 max-w-[230px]">{{ item.description }}</p>
            <ul class="flex flex-col gap-y-3.5 mt-5">
                <li v-for="item in item.features" class="flex gap-x-3"><img src="/img/checkbox-circle.svg" alt="">{{
                    item.description }}</li>
            </ul>
            <button
                class="w-full mt-7 py-3.5 border border-[#00ADB5] rounded-lg text-[#00ADB5] hover:bg-[#00ADB5] hover:text-white duration-300">Choose
                Plan</button>
        </div>
    </div>
</template>
<script setup>
import { ref } from 'vue';

const payment = ref(false);

const free = ([
    {
        id: 1,
        type: 'Free',
        price: '0',
        time: 'Lifetime',
        description: 'For most businesses that want to optiimize web queries',
        features: ([
            {
                description: '50 messages /month',
            },
            {
                description: 'Chat GPT Plus',
            },
            {
                description: '1 custom chatbot',
            },
            {
                description: 'Add files or links',
            },
            {
                description: '3 Files (PDF, DOC, TEXT)',
            },
            {
                description: '60 pages/File',
            },
            {
                description: '10 MB/PDF',
            },
            {
                description: 'Share links with anyone',
            },
            {
                description: 'Embed in your website'
            },
            {
                description: '100+ languages'
            },
            {
                description: 'Email support '
            },
            {
                description: '30-Day Chatbot Access',
            }
        ])
    }
])

const basic = ([
    {
        id: 2,
        type: 'Basic',
        price: '10',
        time: 'Month',
        description: 'For most businesses that want to optiimize web queries',
        features: ([
            {
                description: '1000 messages /month',
            },
            {
                description: 'Chat-GPT Plus (Premium)',
            },
            {
                description: '5 custom chatbot',
            },
            {
                description: 'Add files or links',
            },
            {
                description: '50 Files (PDF, DOC, TEXT)',
            },
            {
                description: '200 pages/File',
            },
            {
                description: '32 MB/PDF',
            },
            {
                description: 'Share links with anyone',
            },
            {
                description: 'Embed in your website'
            },
            {
                description: '100+ languages'
            },
            {
                description: 'Email support '
            },
            {
                description: '30-Day Chatbot Access',
            },
            {
                description: 'Unlimited chatbot access',
            }
        ])
    }
])

const pro = ([
    {
        id: 3,
        type: 'Pro',
        price: '20',
        time: 'Month',
        description: 'For most businesses that want to optiimize web queries',
        features: ([
            {
                description: '5000 messages /month',
            },
            {
                description: 'Chat-GPT Plus (Premium)',
            },
            {
                description: '20 custom chatbot',
            },
            {
                description: 'Add files or links',
            },
            {
                description: '100 Files',
            },
            {
                description: '500 pages/File',
            },
            {
                description: '32 MB/PDF',
            },
            {
                description: 'Share links with anyone',
            },
            {
                description: 'Embed in your website'
            },
            {
                description: '100+ languages'
            },
            {
                description: 'Email support '
            },
            {
                description: '30-Day Chatbot Access',
            },
            {
                description: 'Unlimited chatbot access',
            }
        ])
    }
])

const Business = ([
    {
        id: 3,
        type: 'Business',
        price: '30',
        time: 'Month',
        description: 'For most businesses that want to optiimize web queries',
        features: ([
            {
                description: 'Unlimited messages',
            },
            {
                description: 'Chat-GPT Plus (Premium)',
            },
            {
                description: '50 custom chatbot',
            },
            {
                description: 'Add files or links',
            },
            {
                description: '200 Files',
            },
            {
                description: '1000 pages/File',
            },
            {
                description: '32 MB/PDF',
            },
            {
                description: 'Share links with anyone',
            },
            {
                description: 'Embed in your website'
            },
            {
                description: '100+ languages'
            },
            {
                description: 'Email support '
            },
            {
                description: '30-Day Chatbot Access',
            },
            {
                description: 'Unlimited chatbot access',
            }
        ])
    }
])
</script>
