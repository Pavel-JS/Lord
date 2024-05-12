<template>
  <div class="head">
    <div class="head__log">
      <div class="head__log__icon">
        <img src="/Logo.svg" alt="" />
      </div>
      <div class="head__log_buttons">
        <button class="button1"><a>Войти</a></button>
        <button class="button2"><a>Открыть счет</a></button>
      </div>
    </div>
    <div class="head__menu">
      <div class="head__menu_link">
        <NuxtLink to="">Торговля</NuxtLink>
        <NuxtLink to="">Торговые счета</NuxtLink>
        <NuxtLink to="">MetaTrader 5</NuxtLink>
        <NuxtLink to="">Инструменты</NuxtLink>
        <NuxtLink to="">Партнеру</NuxtLink>
        <NuxtLink to="">О нас</NuxtLink>
      </div>
      <div class="head__menu_lang">
        <img src="/Frame 3.svg" alt="" />
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.head {
  padding: 20px;
  top: 0;
  left: 0;
  right: 0;
  &__log {
    display: flex;
    margin-bottom: 20px;
    justify-content: space-between;
    &_buttons {
      a {
        font-size: 15px;
        font-weight: 600;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
      .button1 {
        cursor: pointer;
        width: 105px;
        height: 40px;
        border: 0;
        color: #1563b7;
        margin-right: 10px;
        background: #f4f4f4;
        border-radius: 4px;
      }
      .button2 {
        cursor: pointer;
        width: 160px;
        height: 40px;
        border: 0;
        color: #ffff;
        background: #1563b7;
        border-radius: 4px;
      }
    }
  }
  &__menu {
    display: flex;
    align-items: center;
    justify-content: space-between;
    &_link {
      a {
        color: #6d6d6d;
        margin-left: 20px;
        font-size: 16px;
        font-weight: 600;
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }
      a:first-child {
        margin-left: 0;
      }
      a:hover {
        color: #1563b7;
      }
    }
  }
}
</style>
