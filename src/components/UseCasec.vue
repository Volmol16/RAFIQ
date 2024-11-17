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
            <div class="cases-card">
                <img class="cases-book-icon" src="/img/book-icon.svg" alt="">
                <h3 class="cases-card-title">
                    Simplified Learning
                </h3>
                <p class="cases-card-description">
                    Rafiq enhances the learning experience by making textbooks, handouts, and presentations more
                    accessible and comprehensible.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-time-icon" src="/img/time.svg" alt="">
                <h3 class="cases-card-title">
                    Time Saving
                </h3>
                <p class="cases-card-description">
                    Quickly find answers from your documents and files, reducing the need for extensive searching and
                    reading.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-medal-icon" src="/img/medal.svg" alt="">
                <h3 class="cases-card-title">
                    Academic Success
                </h3>
                <p class="cases-card-description">
                    Boost your academic performance by effectively utilizing Rafiq's capabilities to support your
                    studies.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-setting-icon" src="/img/setting.svg" alt="">
                <h3 class="cases-card-title">
                    Technical Paper Comprehension
                </h3>
                <p class="cases-card-description">
                    Understand complex technical papers 100x faster with Rafiq's powerful AI-driven analysis.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-document-icon" src="/img/documents.svg" alt="">
                <h3 class="cases-card-title">
                    Summarisation
                </h3>
                <p class="cases-card-description">
                    Effortlessly summarize long papers and extract key information to focus on important points.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-flash-icon" src="/img/flash.svg" alt="">
                <h3 class="cases-card-title">
                    Rapid Learning
                </h3>
                <p class="cases-card-description">
                    Turn intricate technical papers into easy-to-understand summaries and discover new insights quickly.
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
            <div class="cases-card">
                <img class="cases-filter-icon cases-icon" src="/img/documentfilter.svg" alt="">
                <h3 class="cases-card-title">
                    Document Analysis
                </h3>
                <p class="cases-card-description">
                    Efficiently analyze various documents, such as financial reports, project proposals, training
                    manuals, and legal contracts, with Rafiq's AI-driven capabilities.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-security-icon cases-icon" src="/img/securitysafe.svg" alt="">
                <h3 class="cases-card-title">
                    Data Security
                </h3>
                <p class="cases-card-description">
                    Benefit from confidential and secure cloud storage, with the option to delete your data at any time.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-message-icon cases-icon" src="/img/messaget.svg" alt="">
                <h3 class="cases-card-title">
                    Custom Chatbot Creation
                </h3>
                <p class="cases-card-description">
                    Add your content to create a custom ChatGPT and integrate it with your website for a seamless user
                    experience.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-star-icon cases-icon" src="/img/star.svg" alt="">
                <h3 class="cases-card-title">
                    Smart Answers
                </h3>
                <p class="cases-card-description">
                    Save time for customers, employees, and followers by providing faster, more accurate responses to
                    frequently asked questions.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-briefcase-icon cases-icon" src="/img/briefcase.svg" alt="">
                <h3 class="cases-card-title">
                    Enhanced Productivity
                </h3>
                <p class="cases-card-description">
                    Boost company, creator, or brand performance by streamlining communication and minimizing repetitive
                    tasks.
                </p>
            </div>

            <div class="cases-card">
                <img class="cases-layer-icon cases-icon" src="/img/layer.svg" alt="">
                <h3 class="cases-card-title">
                    Content Generation
                </h3>
                <p class="cases-card-description">
                    Automatically generate detailed insights for reports, papers, and various tasks based on your files,
                    streamlining your workflow.
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