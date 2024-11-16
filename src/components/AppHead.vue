<template>
    <header class="header">
        <img src="/img/RAFIQ.svg" alt="">
        <nav class="nav">
            <ul>
                <li><a href="">About</a></li>
                <li><a href="">Features</a></li>
                <li><a href="">Pricing</a></li>
                <li><a href="">Affiliate</a></li>
            </ul>
        </nav>
        <div class="header-buttons">
            <button class="login-btn">Login</button>
            <button class="try-btn">Try it for free</button>
        </div>
    </header>
</template>

<style scoped>
    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: black;
    }

    ul {
        display: flex;
        column-gap: 30px;
    }

    a {
        text-decoration: none;
        font-size: 15px;
        font-weight: 500;
        line-height: 18.15px;
        color: #fff;
    }

    .login-btn {
        padding: 8px 17px;
        color: #fff;
        font-size: 15px;
        font-weight: 500;
        line-height: 18.15px;
    }

    .try-btn {
        padding: 8px 17px;
        color: #fff;
        font-size: 15px;
        font-weight: 500;
        line-height: 18.15px;
        background-color: #00ADB5;
        border: none;
        border-radius: 9px;
    }
</style>