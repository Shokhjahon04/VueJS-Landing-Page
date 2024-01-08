<script setup>
import { RouterLink } from 'vue-router';

// SHOW MENU
function add() {
  const navMenu = document.querySelector('.nav__menu')
  navMenu.classList.add('show-menu')
}

// CLOSE MENU
function close() {
  const navMenu = document.querySelector('.nav__menu')
  navMenu.classList.remove('show-menu')
}

</script>

<template>
    <header class="header" id="header">
        <nav class="nav container">
            <RouterLink to="/">
                <img src="../assets/img/logo.png" alt="" class="nav__logo">
                <!-- logo mobile -->
                <img src="../assets/img/logo-mobile.png" alt="" class="nav__logo-mobile">
            </RouterLink>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item">
                        <RouterLink to="/" class="nav__link" @click="close()">HOME</RouterLink>
                    </li>
                    <li class="nav__item">
                        <RouterLink to="/about" class="nav__link" @click="close()">ABOUT</RouterLink>
                    </li>
                    <li class="nav__item">
                        <RouterLink to="/pricing" class="nav__link" @click="close()">PRICING</RouterLink>
                    </li>
                    <li class="nav__item">
                        <RouterLink to="/token" class="nav__link" @click="close()">TOKENS</RouterLink>
                    </li>
                </ul>

                <div class="nav__close" @click="close()">
                    <i class="ri-close-line"></i>
                </div>
            </div>

            <a href="#" class="nav__d-btn button-main">
                DOWNLOAD APP
            </a>

            <div class="nav__toggle" @click="add()">
                <i class="ri-menu-line"></i>
            </div>
        </nav>
    </header>   
</template>

<style scoped>
/*=============== HEADER ===============*/
.header{
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    background-color: var(--body-color);
    z-index: var(--z-fixed);
    /* border: 1px solid white; */
}

/* Change background header */
.scroll-header{
    box-shadow: 0 1px 4px #01105a;
}

/*=============== NAV ===============*/
.nav{
    height: 4rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav__logo,
.nav__toggle,
.nav__close{
  color: var(--text-color);
}

.nav__logo,
.nav__logo-mobile{
    width: 125px;
    display: inline-flex;
    transition: .3s;
}

.nav__logo{
    display: none;
}

.nav__toggle{
    display: inline-flex;
    font-size: 1.25rem;
    cursor: pointer;
}

.nav__d-btn{
    padding: 20px 25px;
    display: none;
}

@media screen and (max-width: 767px){
    .nav__menu{
      position: fixed;
      background-color: var(--body-color);
      width: 100%;
      height: 100%;
      top: -100%;
      right: 0;
      padding: 4rem 0 0 3rem;
      transition: .3s;
      z-index: var(--z-fixed);
    }
}

.nav__close{
    font-size: 1.5rem;
    position: absolute;
    top: 1rem;
    right: 1.25rem;
    cursor: pointer;
}

.nav__list{
    display: flex;
    flex-direction: column;
    row-gap: 1.5rem;
}

.nav__link{
    color: var(--text-color);
    font-weight: var(--font-medium);
    transition: .3s;
}

/* Show menu */
.show-menu{
    top: 0;
}

/*=============== NAVBAR BREAKPOINTS ===============*/
@media screen and (min-width: 767px){
    .nav{
        height: calc(var(--header-height) + 1.5rem);
        column-gap: 3rem;
    }

    .nav__logo-mobile{
        display: none;
    }

    .nav__logo{
        display: block;
        width: 180px;
    }

    .nav__toggle,
    .nav__close{
        display: none;
    }

    .nav__list{
        flex-direction: row;
        column-gap: 3rem;
    }

    .nav__menu{
        margin-left: auto;
    }
}

@media screen and (min-width: 1200px){
    .nav__d-btn{
        display: inline-flex;
        margin-left: 100px;
    }
}
</style>