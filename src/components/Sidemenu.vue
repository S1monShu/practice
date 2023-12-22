<template>
    <div class="side-menu__container">
        <div class="main-options">
            <ul>
                <li><img src="../assets/ph_house-light.png" alt=""><a href="#">Главная</a></li>
                <li><img src="../assets/ph_chat-text-light.png" alt=""><a href="#">Сообщения</a></li>
                <li><img src="../assets//ph_user-circle-light.png" alt=""><a href="#">Друзья</a></li>
            </ul>
        </div>
        <div class="create-post__btn">
            <img src="../assets/ph_plus-square-light.png" alt="">
            <a href="#">Создать пост</a>
        </div>
        <div class="other-options">
            <ul>
                <li><img src="../assets/ph_gear-six-light.png" alt=""><a href="#">Настройки</a></li>
                <li class="exit"><img src="../assets/ph_door-open-light.png" alt=""><a href="#">Выйти</a></li>
            </ul>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
.side-menu__container {
    padding: 5px 20px;
    height: fit-content;
    border-radius: 17px;
    width: 198px;
    font-family: 'Century Gothic';
    font-weight: bold;
    font-size: 14px;
}

ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

ul li {
    display: flex;
    align-items: center;
    padding: 15px 0px;
    border-bottom: 1px solid #F2F2F2;
}

ul li img {
    margin-right: 15px;
}

ul li a {
    text-decoration: none;
    color: #000;
}

.create-post__btn {
    margin-top: 15px;
    padding: 9px 0px;
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(135deg, rgba(69, 30, 97, 1) 0%, rgba(251, 143, 107, 1) 100%);
    border-radius: 7px;
    cursor: pointer;
}

.create-post__btn img {
    margin-right: 10px;
}

.create-post__btn a {
    text-decoration: none;
    color: #FFF;
}

.other-options {
    margin-top: 280px;
}

.other-options .exit {
    border: none;
}
</style>