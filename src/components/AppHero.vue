<template>
    <section class="hero">
        <div class="hero-info">
        <h1 class="hero-title">
            ChatGPT, but with your own <span>Data</span>
        </h1>
        <p class="hero-description">
            Effortlessly create AI chatbots tailored to your data, documents, or files, and experience limitless general
            chatting with ChatGPT. Boost your productivity, learning, and research with the power of AI at your
            fingertips
        </p>
        <div class="get-started">
            <button class="get-started-btn">
                Get started ->
            </button>
            <div class="get-started-avatar">
                <img class="z-0" src="/img/Avatar-1.png" alt="avatar">
                <img class="z-10" src="/img/Avatar-2.png" alt="avatar">
                <img class="z-20" src="/img/Avatar-3.png" alt="avatar">
            </div>
            <p class="get-started-join">
                Join with 10,000+ users
            </p>
        </div>
    </div>
    <div class="hero-image">
        <img src="/img/cuate.png" width="593" height="525" alt="">
    </div>
    </section>
</template>

<style scoped>
    .hero {
        margin-top: 108px;
        display: flex;
        align-items: center;
    }

    .hero-title {
        margin-bottom: 40px;
        width: 706px;
        font-size: 70px;
        font-weight: 800;
        line-height: 84px;
        color: #fff;
    }

    .hero-title span {
        font-size: 70px;
        font-weight: 800;
        line-height: 84px;
        color: #00ADB5;
    }

    .hero-description {
        margin-bottom: 56px;
        width: 545px;
        font-size: 14px;
        font-weight: 500;
        line-height: 24px;
        opacity: 60%;
        color: #fff;
    }

    .get-started {
        display: flex;
        column-gap: 17px;
    }

    .get-started-btn {
        padding: 14px 40px;
        font-size: 15px;
        font-weight: 500;
        line-height: 18.15px;
        border: none;
        border-radius: 9px;
        color: #263238;
        background-color: #fff;
    }

    .get-started-avatar {
        display: flex;
    }

    .get-started-join {
        /* width: 140px; */
        font-size: 14px;
        font-weight: 400;
        line-height: 15.23px;
        color: #fff;
    }
</style>