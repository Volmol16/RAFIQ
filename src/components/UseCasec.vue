<template>
    <section class="use-cases">
        <h2 class="use-cases-title]">
            <b>Use Cases</b>
        </h2>
        <p class="use-cases-description">
            let’s dicuss how you can use RAFIQ and get its maximum values
        </p>

        <!-- STUDENTS -->

        <div class="students-img">
            <h3 class="cases-title">
                for students
            </h3>
        </div>
        <div class="cases-cards">
            <div v-for="item in casesCardStudents" :key="item.id" class="cases-card">
                <img class="" :src="item.img" alt="">
                <h3 class="cases-card-title mt-10">
                    {{ item.title }}
                </h3>
                <p class="cases-card-description">
                    {{ item.description }}
                </p>
            </div>
        </div>

        <!-- WORK -->

        <div class="work-img">
            <h3 class="cases-title">
                for work, business & companies
            </h3>
        </div>
        <div class="cases-cards">
            <div v-for="item in casesCardWork" :key="item.id" class="cases-card">
                <img class="" :src="item.img" alt="">
                <h3 class="cases-card-title mt-10">
                    {{ item.title }}
                </h3>
                <p class="cases-card-description">
                    {{ item.description }}
                </p>
            </div>
        </div>

    </section>
</template>

<style scoped>
.use-cases-title {
    text-align: center;
    margin-bottom: 20px;
    font-size: 48px;
    font-weight: 400;
    line-height: 52.22px;
    color: #fff;
}

.use-cases-description {
    text-align: center;
    margin-bottom: 40px;
    font-size: 18px;
    font-weight: 400;
    line-height: 26px;
    color: #999999;
    opacity: 60%;
}

/* STUDENTS */

.students-img {
    margin-bottom: 80px;
    padding-top: 117px;
    background-image: url(/img/students.png);
    background-size: no-repeat;
    background-position: center;
    background-size: cover;
    width: 1440px;
    height: 265px;
    max-width: 1280px;
}

.cases-title {
    text-transform: uppercase;
    text-align: center;
    font-size: 24px;
    font-weight: 700;
    line-height: 29.05px;
    color: #fff;
}

.cases-cards {
    margin-bottom: 50px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.cases-card {
    margin-bottom: 30px;
    width: 340px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.cases-book-icon {
    margin-bottom: 40px;
    padding: 24px;
    border-radius: 4px;
    background-color: #E2F8F880;
}

.cases-time-icon {
    margin-bottom: 40px;
    padding: 24px;
    border-radius: 4px;
    background-color: #B6AFFF80;
}

.cases-medal-icon {
    margin-bottom: 40px;
    padding: 24px;
    border-radius: 4px;
    background-color: #F3EBE380;
}

.cases-setting-icon {
    margin-bottom: 40px;
    padding: 24px;
    border-radius: 4px;
    background-color: #E3F3E480;
}

.cases-document-icon {
    margin-bottom: 40px;
    padding: 24px;
    border-radius: 4px;
    background-color: #F8C4B480;
}

.cases-flash-icon {
    margin-bottom: 40px;
    padding: 24px;
    border-radius: 4px;
    background-color: #7FBCD266;
}

.cases-card-title {
    margin-bottom: 16px;
    text-align: center;
    font-size: 24px;
    font-weight: 500;
    line-height: 32px;
    ;
    color: #fff;
}

.cases-card-description {
    text-align: center;
    font-size: 16px;
    font-weight: 400;
    line-height: 22px;
    color: #999999;
    opacity: 60%;
}

/* WORK */

.work-img {
    margin-bottom: 80px;
    padding-top: 117px;
    background-image: url(/img/work.png);
    background-size: no-repeat;
    background-position: center;
    background-size: cover;
    width: 1440px;
    height: 265px;
    max-width: 1280px;
}

.cases-icon {
    margin-bottom: 40px;
    padding: 24px;
    border-radius: 4px;
}

.cases-filter-icon {
    background-color: #CCD6A680;
}

.cases-security-icon {
    background-color: #A555EC66;
}

.cases-message-icon {
    background-color: #7FE9DE66;
}

.cases-star-icon {
    background-color: #EAC7C799;
}

.cases-briefcase-icon {
    background-color: #E3C77066;
}

.cases-layer-icon {
    background-color: #A0BCC280;
}
</style>

<script setup>

const casesCardStudents = ([
    {
        id: 1,
        img: '/usecases/1.png',
        title: 'Simplified Learning',
        description: 'Rafiq enhances the learning experience by making textbooks, handouts, and presentations more accessible and comprehensible.'
    },
    {
        id: 2,
        img: '/usecases/2.png',
        title: 'Time Saving',
        description: 'Quickly find answers from your documents and files, reducing the need for extensive searching and reading.'
    },
    {
        id: 3,
        img: '/usecases/3.png',
        title: 'Data-Driven Insights',
        description: 'Rafiq provides data-driven insights, enabling organizations to make informed decisions based on the data provided.'
    },
    {
        id: 4,
        img: '/usecases/4.png',
        title: 'Customization',
        description: 'Rafiq allows users to create custom chatbots that align with their specific needs and preferences.'
    },
    {
        id: 5,
        img: '/usecases/5.png',
        title: 'Document Management',
        description: 'Rafiq simplifies document management by providing a user-friendly interface for uploading, organising, and sharing documents.'
    },
    {
        id: 6,
        img: '/usecases/6.png',
        title: 'Data Security',
        description: 'Rafiq ensures the security of data by encrypting it and implementing robust security measures to protect against unauthorized access.'
    }
])

const casesCardWork = ([
    {
        id: 7,
        img: '/usecases/7.png',
        title: 'Document Analysis',
        description: "Efficiently analyze various documents, such as financial reports, project proposals, training manuals, and legal contracts, with Rafiq's AI-driven capabilities."
    },
    {
        id: 8,
        img: '/usecases/8.png',
        title: 'Data Security',
        description: "Benefit from confidential and secure cloud storage, with the option to delete your data at any time."
    },
    {
        id: 9,
        img: '/usecases/9.png',
        title: 'Custom Chatbot Creation',
        description: "Add your content to create a custom ChatGPT and integrate it with your website for a seamless user experience."
    },
    {
        id: 10,
        img: '/usecases/10.png',
        title: 'Smart Answers',
        description: "Save time for customers, employees, and followers by providing faster, more accurate responses to frequently asked questions."
    },
    {
        id: 11,
        img: '/usecases/11.png',
        title: 'Enhanced Productivity',
        description: "Boost company, creator, or brand performance by streamlining communication and minimizing repetitive tasks."
    },
    {
        id: 12,
        img: '/usecases/12.png',
        title: 'Content Generation',
        description: "Automatically generate detailed insights for reports, papers, and various tasks based on your files, streamlining your workflow."
    },
]) 

</script>