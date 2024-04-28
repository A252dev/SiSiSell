<script>

    import '@/assets/styles/UI/Header.css'

    export default {

    }
</script>

<template>
    <div className="header">
        <a className="logo__link" href="#"><img className="logo" src="@/assets/img/logo.png" alt="logo" /></a>
        <nav className="links__container">
            <a className="current__link" href="#">Главная</a>
            <a className="current__link" href="#">Соглашение</a>
            <a className="current__link" href="#">Лотерея</a>
            <a className="current__link" href="#">Поддержка</a>
        </nav>
        <nav className="social__container">
            <a className="social__link" href="#"><img className="social__logo" src="@/assets/img/telegram.png" alt="telegram" /></a>
            <a className="social__link" href="#"><img className="social__logo" src="@/assets/img/vk.png" alt="vk" /></a>
            <a className="social__link" href="#"><img className="social__logo" src="@/assets/img/youtube.png" alt="youtube" /></a>
        </nav>
        <nav className="account__container">
            <a className="account__link" href="#">Войти</a>
            <a className="account__link" href="#">Регистрация</a>
        </nav>
    </div>
</template>