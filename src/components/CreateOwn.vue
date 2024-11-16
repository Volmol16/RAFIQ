<template>
    <div class="px-16 py-12 bg-[#263238] rounded-2xl">
        <h2 class="text-5xl font-bold text-white text-center"><span class="text-[#00ADB5]">Create Your Own</span> Custom
            <br>
            Chat-GPT in
            10 Seconds.
        </h2>
        <div class="grid grid-cols-2 gap-5 mt-11">

            <div v-for="item in cardItems" class="p-7 bg-[#f9f9fc0c] rounded-sm flex-col items-start gap-y-2.5 flex">
                <img :src="item.img" alt="">
                <h4 class="text-lg text-white font-bold">{{ item.title }}</h4>
                <p class="text-sm text-[#999999] max-w-[360px]">{{ item.description }}</p>
            </div>
        </div>
    </div>
</template>
<script setup>


const cardItems = ([
    {
        img: '/CreateOwn/1.svg',
        title: 'Upload your documents.',
        description: 'Upload links and documents or any content you want to ask questions to.'
    },
    {
        img: '/CreateOwn/2.svg',
        title: 'Create your chatbot.',
        description: 'Customise how it looks and responds to questions. All powered by ChatGPT.'
    },
    {
        img: '/CreateOwn/3.svg',
        title: 'Start talking with it.',
        description: 'Upload links and documents or any content you want to ask questions to.'
    },
    {
        img: '/CreateOwn/4.svg',
        title: 'Embed & Share Your Chatbot on Your Website.',
        description: 'upload links and documents, customise chatbot appearance and responses with ChatGPT.'
    }
])
</script>
