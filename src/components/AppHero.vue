<template>
    <section class="hero">
        <div class="hero-info">
            <h1 class="hero-title">
                ChatGPT, but with <br> your own <span>Data</span>
            </h1>
            <p class="hero-description">
                Effortlessly create AI chatbots tailored to your data, documents, or files, and experience limitless
                general
                chatting with ChatGPT. Boost your productivity, learning, and research with the power of AI at your
                fingertips
            </p>
            <div>
                <button class="px-10 py-3.5 bg-white text-black rounded-xl">Get started -></button>
            </div>
        </div>
        <div class="hero-image">
            <img src="/img/cuate.png" width="593" height="525" alt="">
        </div>

    </section>
    <div class="flex flex-col items-center justify-center pb-10 border-b border-[#00acb57a] mt-80">
        <span class="text-[#ffffff60]">Powered By </span>
        <div class="flex text-white gap-x-[88px] items-center mt-5">
            <img src="/img/OpenAi.svg" alt="">
            <img src="/img/cohere.svg" alt="">
            <h4 class="text-2xl text-[#ABABAB]">ANTHROP\C</h4>
        </div>
    </div>
</template>

<style scoped>
.hero {
    margin-top: 108px;
    display: flex;
    align-items: center;
}

.hero-title {
    margin-bottom: 40px;
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
    font-size: 14px;
    font-weight: 400;
    line-height: 15.23px;
    color: #fff;
}
</style>