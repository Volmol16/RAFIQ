<template>
    <section class="try-rafiq">
        <div class="try-rafiq-content">
            <div class="try-rafiq-info">
                <h2 class="try-rafiq-title">
                    <b>Try <span>RAFIQ</span> <br> By <br>Yourself</b>
                </h2>
                <p class="try-rafiq-description">
                    This chat has been created by a file that has all of Rafiq's information in it.
                </p>
                <button class="try-rafiq-btn">
                    Try it for free
                </button>
            </div>
            <img src="/img/try-rafiq-img.png" width="430" alt="">
        </div>
    </section>
</template>

<style scoped>
.try-rafiq {
    padding: 158px 200px;
    background-image: url(/img/try-rafiq-bacground.png);
    background-size: no-repeat;
    background-position: center;
    background-size: cover;
    width: 1439px;
    height: 846px;
    max-width: 1280px;

}

.try-rafiq-content {
    padding-top: 78px;
    padding-bottom: 90px;
    padding-left: 60px;
    display: flex;
    border-radius: 15px;
    background-color: #263238;
}

.try-rafiq-title {
    margin-bottom: 20px;
    width: 390px;
    font-size: 64px;
    font-weight: 400;
    line-height: 69.63px;
    color: #fff;
}

.try-rafiq-title span {
    color: #00ADB5;
}

.try-rafiq-description {
    margin-bottom: 40px;
    width: 352px;
    font-size: 16px;
    font-weight: 400;
    line-height: 26px;
    color: #999;
    opacity: 60%;
}

.try-rafiq-btn {
    padding: 12px 66px;
    background-color: #00ADB5;
    border: none;
    border-radius: 10px;
    color: #fff;
    font-size: 15px;
    font-weight: 500;
    line-height: 18.15px;
    transition: all 0.3s ease;
}

.try-rafiq-btn:hover {
    background-color: #00acb5c4;
}
</style>