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
    transition: all 0.3s ease;
}

a:hover {
    color: #ffffffc2;
}

.login-btn {
    padding: 8px 17px;
    color: #fff;
    font-size: 15px;
    font-weight: 500;
    line-height: 18.15px;
    transition: all 0.3s ease;
}

.login-btn:hover {
    color: #ffffffc2;
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
    transition: all 0.3s ease;
}

.try-btn:hover {
    background-color: #00acb5c4;
}
</style>