<template>
    <div class="post__container">
        <div class="user">
            <div class="avatar-img">
                <img src="../assets/avatar.png" alt="">
            </div>
            <div class="user-info">
                <p class="name">Иван Иванов</p>
                <p class="date">сегодня 12:46</p>
            </div>
        </div>
        <div class="post__img">
            <img src="../assets/unsplash_gOqBe7ropxM.png" alt="">
        </div>
        <div class="tags__container">
            <Tag />
        </div>
    </div>
</template>

<script setup>
import Tag from '../components/Tag.vue'
</script>

<style>
.post__container {
    background-color: #FFF;
    height: fit-content;
    width: 754px;
    border-radius: 17px;
    padding: 20px;
}

.user {
    display: flex;
    margin-bottom: 20px;
}

.avatar-img {
    margin-right: 15px;
}

.user-info {
    font-family: 'Century Gothic';
    font-size: 14px;
}

.date {
    color: #7A7A7A;
}

.post__img {
    border-radius: 7px;
    margin-bottom: 20px;
}
</style>