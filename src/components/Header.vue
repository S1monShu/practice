<template>
    <header>
        <h1>Logo</h1>
        <div class="user-avatar__container">
            <img src="../assets/avatar.png" alt="">
        </div>
    </header>
</template>
<script></script>
<style scoped>
header {
    height: 80px;
    display: flex;
    padding: 0px 325px;
    justify-content: space-between;
    align-items: center;
}

h1 {
    font-family: 'Century Gothic';
    font-size: 36px;
}

.user-avatar__container {
    position: relative;
    display: flex;
    height: 48px;
    width: 48px;
    border-radius: 100px;
    background: #fff;
    justify-content: center;
    align-items: center;
}

.user-avatar__container::before {
    content: "";
    position: absolute;
    top: -2px;
    bottom: -2px;
    left: -2px;
    right: -2px;
    background: linear-gradient(135deg, rgba(69, 30, 97, 1) 0%, rgba(251, 143, 107, 1) 100%);
    border-radius: 100px;
    z-index: -1;
}

.user-avatar__container img {
    border-radius: 100px;
}
</style>