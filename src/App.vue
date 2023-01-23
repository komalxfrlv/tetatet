<template>
  <nav>
    <div class="logo">
      <img src="./assets/logo.jpg" alt="logo" />
    </div>
    <div class="links">
      <div><router-link to="/">Главная</router-link></div>
      <div><router-link to="/about">О нас</router-link></div>
      <div><router-link to="/price">Цены</router-link></div>
      <div><router-link to="/portfolio">Портфолио</router-link></div>
      <div><router-link to="/order">Заказать</router-link></div>
    </div>

  </nav>
  <router-view />
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200;300;400;500;600;700;800&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.home {
  padding-top: 82px;
}

#app {
  font-family: 'Manrope', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  width: 100%;
  padding: 30px;
  position: fixed;
  background-attachment: fixed;
  background-color: white;

  .logo {
    float: left;

    img {
      height: 79px;
      position: absolute;
      margin-top: -25px;
    }

  }

  .links {
    display: flex;
    justify-content: flex-end;

    div {
      margin: 0px 20px;
    }
  }

  .logo {
    justify-content: flex-end;
  }

  a {
    transition: 250ms;
    font-weight: 300;
    color: #2c3e50;
    font-size: 16pt;
    text-decoration: none;

    &.router-link-exact-active {
      color: #e9483d;
      font-weight: bold;
    }
  }
}
</style>
