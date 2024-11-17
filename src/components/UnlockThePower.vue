<template>
    <section class="premium">
        <h2 class="premium-title">
            <b>Unlock <span>The Power</span> of Chat-GPT+ premium</b>
        </h2>
        <div class="premium-cards-list">
          <div v-for="item in premiumCard" :key="item.id" class="premium-card">
            <img class="premium-card-img" :src="item.img" alt="">
            <h3 class="premium-card-title">
                {{ item.title }}
            </h3>
            <p class="premium-card-description">
                {{  item.description }}
            </p>
          </div>
        </div>

        <h2 class="premium-title mt-5">
            <b>Unlock The Power of Custom Chat- <br>GPT with <span>Your Own Data</span> and <br> documents</b>
        </h2>
        <div class="premium-cards-list">
          <div v-for="item in customgptCard" :key="item.id" class="premium-card">
            <img class="premium-card-img" :src="item.img" alt="">
            <h3 class="premium-card-title">
                {{ item.title }}
            </h3>
            <p class="premium-card-description">
                {{  item.description }}
            </p>
          </div>
        </div>
    </section>
</template>

<script setup>
    const premiumCard = ([
        {
            id: 1,
            img: 'UnlockThePower/1.png',
            title: 'Enhanced Content Generation',
            description: 'ChatGPT+ can effortlessly generate high-quality content for articles, blogs, social media, and more, helping you save time and boost your creative output.',
        },
        {
            id: 2,
            img: 'UnlockThePower/2.png',
            title: 'Multilingual Support',
            description: "Cater to a global audience with ChatGPT+'s ability to understand and respond in multiple languages, making your chatbot accessible to users worldwide.",
        },
        {
            id: 3,
            img: 'UnlockThePower/3.png',
            title: 'Conversations',
            description: 'Benefit from context-aware conversations that offer a seamless user experience by maintaining context throughout interactions, making exchanges feel more natural',
        },
        {
            id: 4,
            img: 'UnlockThePower/4.png',
            title: 'Advanced Customisation',
            description: 'Personalize your chatbot to match your brand identity by customizing features like avatars, placeholder text, answer visibility, and source references.',
        },
        {
            id: 5,
            img: 'UnlockThePower/5.png',
            title: 'In-Depth Analytics & Reporting',
            description: 'Gain valuable insights on chatbot performance with detailed analytics and reporting features, enabling you to make data-driven decisions to improve user experience and engagement.',
        },
        {
            id: 6,
            img: 'UnlockThePower/6.png',
            title: 'Access to General Knowledge',
            description: 'Utilise the general ChatGPT for a vast range of topics, giving users access to a wealth of knowledge without the need for custom data input, ensuring a informative chatbot experience.',
        },
    ])

    const customgptCard = ([
        {
            id: 7,
            img: 'UnlockThePower/7.png',
            title: 'Targeted Knowledge Extraction',
            description: 'Custom ChatGPT leverages your specific data, documents, websites, or books to provide tailored answers and insights, making it a powerful resource for specialized information.',
        },
        {
            id: 8,
            img: 'UnlockThePower/8.png',
            title: 'Document Summarisation',
            description: "Turn lengthy documents into concise summaries, allowing users to quickly grasp key information and insights from your data without wading through pages of text.",
        },
        {
            id: 9,
            img: 'UnlockThePower/9.png',
            title: 'Seamless Content Integration',
            description: 'Easily integrate a wide range of content formats (PDF, DOC, DOCX, TXT, CSV) or URLs, enabling the chatbot to access and utilize the most relevant information.',
        },
        {
            id: 10,
            img: 'UnlockThePower/10.png',
            title: 'Contextual FAQ Assistance',
            description: 'Generate contextual FAQs based on your uploaded data, offering users an enhanced support experience tailored to their needs and specific queries.',
        },
        {
            id: 11,
            img: 'UnlockThePower/11.png',
            title: 'Automatic Content Curation',
            description: 'Custom ChatGPT can automatically curate content based on your data, creating a dynamic knowledge base that keeps users engaged and informed.',
        },
        {
            id: 12,
            img: 'UnlockThePower/12.png',
            title: 'Niche Expertise Development',
            description: 'Develop a chatbot with niche expertise by training it on your specialized data, making it an invaluable resource for users seeking expert guidance in a specific domain.',
        },
    ])
</script>

<style scoped>
/* PREMIUM */

    .premium-title {
        margin-bottom: 46px;
        font-size: 48px;
        font-weight: 400;
        line-height: 52.22px;
        text-align: center;
        color: #fff;
    }

    .premium-title span {
        color: #00ADB5;
    }

    .premium-cards-list {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        justify-content: center;
        gap: 25px;
    }

    .premium-card {
        padding: 40px 30px;
        width: 380px;
        height: 314px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        background-color: #0a0a0a;
        border: 2px solid #FFFFFF0D;
        border-radius: 15px;
    }

    .premium-card-img {
        margin-bottom: 22px;
        width: 60px;
        height: 60px;
    }

    .premium-card-title {
        width: 300px;
        margin-bottom: 13px;
        font-size: 21px;
        font-weight: 700;
        line-height: 25.41px;
        color: #fff;
        
    }

    .premium-card-description {
        width: 320px;
        font-size: 14px;
        font-weight: 500;
        line-height: 22px;
        color: #999;
        opacity: 80%;
    }

    /* CUSTOMGPT */

    .customgpt-title {
        width: 1018px;
        margin-bottom: 46px;
        font-size: 48px;
        font-weight: 400;
        line-height: 52.22px;
        text-align: center;

        color: #fff;
    }

    .customgpt-title span {
        color: #00ADB5;
    }

    .customgpt-cards-list {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 25px;
    }

    .customgpt-card {
        padding: 40px 30px;
        width: 380px;
        height: 314px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        background-color: #0a0a0a;
        border: 2px solid #FFFFFF0D;
        border-radius: 15px;
    }

    .customgpt-card-img {
        margin-bottom: 22px;
        width: 60px;
        height: 60px;
    }

    .customgpt-card-title {
        width: 300px;
        margin-bottom: 13px;
        font-size: 21px;
        font-weight: 700;
        line-height: 25.41px;
        color: #fff;
        
    }

    .customgpt-card-description {
        width: 320px;
        font-size: 14px;
        font-weight: 500;
        line-height: 22px;
        color: #999;
        opacity: 80%;
    }
</style>