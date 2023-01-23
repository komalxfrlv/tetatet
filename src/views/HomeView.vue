<template>
  <div class="home">

    <div class="hello">
      <div class="row">
        <div class="col-shaped">
          <div class="shaped-box">
          </div>
        </div>
        <div class="col-welcome">
          <div class="welcome-text">
            <h1 class="welcome-header">Мебель<br>Premium класса</h1>
            <p class="welcome-info">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
              incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
              laboris nisi ut aliquip ex</p>
          </div>
        </div>
      </div>
    </div>

    <div class="about-us-background">
      <div class="about-us">
        <h1 class="about-us-header"><span class="">Немного о нас</span></h1>
        <div class="about-goals">
          <div class="goals-row">
            <div class="goals-column">
              <img src="./../assets/workers-male.svg" />
              <h2>Опытные мастера</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                incididunt ut labore et dolore magna aliqua
              </p>
            </div>
            <div class="goals-column">
              <img src="./../assets/blueprint.svg" />
              <h2>Бесплатный замер</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                incididunt ut labore et dolore magna aliqua
              </p>
            </div>
            <div class="goals-column">
              <img src="./../assets/manufacturing.svg" />
              <h2>Свое производство</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                incididunt ut labore et dolore magna aliqua
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="our-works">
      <h1>Наши работы</h1>
      <div class="gallery">
        <div class="gallery-row">
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
        </div>
        <div class="gallery-row">
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
        </div>
        <div class="gallery-row">
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
          <div class="gallery-column">
            <div class="holder">
              <img src="./../assets/background.jpg" alt="">
            </div>
          </div>
        </div>
      </div>
      <p class="portfolio-info">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
        incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
        laboris nisi ut aliquip ext ut labo consectetur elit sed do eiusmod
      </p>
    </div>



    <div class="make-order">
      <div class="order-container">
        <div class="order-row">
          <div class="order-column">
            <div class="order-form">
              <div class="input-field-box">
                <input type="text" class="input-field" placeholder="Ваше имя">
              </div>
              <div class="input-field-box">
                <input type="text" class="input-field" placeholder="Ваш телефон">
              </div>
              <div class="input-field-box">
                <textarea placeholder="Оставьте нам сообщение :)"></textarea>
              </div>
              <div class="button-box">
                <div class="button">
                  СВЯЗАТЬСЯ С НАМИ
                </div>
              </div>
            </div>
          </div>
          <div class="order-column">
            <div class="order-text">
              <h1>Давайте обсудим проект?</h1>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                incididunt ut labore et dolore magna aliqua.
              </p>
              <div class="other-services">
                Дополнительные услуги
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="contacts">
      <div class="contacts-row">
        <div class="contacts-column">
          <iframe
            src="https://yandex.ru/map-widget/v1/?um=constructor%3A376039479fca98c678d67e15b023fed8368aabb249658db585174d5c7ed004d7&amp;source=constructor"
            width="100%" height="450" frameborder="0"></iframe>
        </div>
        <div class="contacts-column">
          <div class="contacts-container">
            <div class="contacts-block">
              <h4>Address</h4>
              <address>66, Dang Van ngu, Dong Da,<br> Ha noi, Vietnam</address>
            </div>
            <div class="contacts-block">
              <h4>Email</h4>
              <a href="mailto:contact@halovietnam.com">contact@halovietnam.com</a>
            </div>
            <div class="contacts-block">
              <h4>Phone</h4>
              <a href="tel:+844123456789">+844 1234 56789</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="footer">
      TET A TET &copy; 2023
    </div>

  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    //HelloWorld
  }
}
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Poiret+One&display=swap');

.shaped-box {
  border-radius: 30% 70% 67% 33% / 30% 35% 65% 70%;
  width: 400px;
  height: 400px;
  background: rgb(251, 235, 64);
  background: linear-gradient(120deg, rgba(251, 235, 64, 1) 0%, rgba(247, 162, 55, 1) 35%, rgba(233, 72, 61, 1) 100%);
  margin: 0 auto;
}

.welcome-header {
  font-family: 'Poiret One', cursive;
  font-size: 72pt;
}

.hello {
  min-height: 100vh;
  padding-top: 140px;
}

.row {
  display: flex;
  flex-direction: row;

  .col-shaped {
    width: 40%;
    padding: 50px;
  }

  .col-welcome {
    width: 60%;
    padding: 50px;

    .welcome-text {
      padding: 50px;
    }

    .welcome-info {
      padding-top: 20px;
      width: 70%;
      font-size: 18px;
      margin: 0 auto;
    }
  }
}

.about-us-background {
  min-height: 900px;
  background: url('./../assets/background.jpg');
  background-position: center;
  background-attachment: fixed;
  background-size: cover;

  .about-us {
    width: 100%;
    min-height: 900px;
    background: rgb(251, 235, 64);
    background: linear-gradient(120deg, rgba(251, 235, 64, 0.5) 0%, rgba(247, 162, 55, 0.5) 35%, rgba(233, 72, 61, 0.5) 50%);

    .about-us-header {
      padding-top: 100px;
      color: white;
      font-weight: 800;
      font-size: 68px;
      text-transform: uppercase;
      word-spacing: 30px;
      text-shadow: 1px 1px 35px rgba(0, 0, 0, 0.416);
    }

    .about-goals {
      width: 80%;
      margin: 0 auto;
      color: white;
      padding-top: 100px;

      .goals-row {
        display: flex;
        flex-direction: row;

        .goals-column {
          width: 33.33%;
          padding: 50px;

          img {
            fill: white;
          }

          h2 {
            margin-top: 35px;
            text-transform: uppercase;
            font-weight: 300;
            font-size: 36px;
            margin-bottom: 10px;
          }

          p {
            font-size: 18px;
          }
        }
      }
    }
  }
}

.our-works {
  min-height: 800px;

  .portfolio-info {
    max-width: 700px;
    font-size: 22px;
    margin: 0 auto;
    padding-top: 20px;
    padding-bottom: 50px;
  }

  h1 {
    padding-top: 60px;
    font-weight: 800;
    font-size: 68px;
    text-transform: uppercase;
    word-spacing: 30px;
    margin-bottom: 40px;
  }

  .gallery {
    max-width: 1200px;
    margin: 20px auto;
  }

  .gallery-row {
    display: flex;
    flex-direction: row;

    .gallery-column {
      width: 33.33%;
      margin: 15px;

      .holder {
        background: rgb(251, 235, 64);
        background: linear-gradient(160deg, rgba(251, 235, 64, 1) 0%, rgba(247, 162, 55, 1) 35%, rgba(233, 72, 61, 1) 50%);
        width: 360px;
        height: 227px;
        padding: 3px;
        border-radius: 8px;

        img {
          width: 100%;
          height: auto;
          border-radius: 8px;
        }
      }
    }
  }
}

.make-order {

  background: rgb(251, 235, 64);
  background: linear-gradient(20deg, rgba(251, 235, 64, 1) 0%, rgba(247, 162, 55, 1) 35%, rgba(233, 72, 61, 1) 50%);
}

.order-row {
  display: flex;
  flex-direction: row;

  .order-column {
    width: 50%;
  }
}

.input-field-box {
  margin-top: 10px;
  margin-bottom: 10px;

  input {
    padding: 8px;
    border-radius: 6px;
    font-size: 22px;
    font-weight: 300;
    border: none;
    width: 400px;
  }

  textarea {
    padding: 8px;
    border-radius: 6px;
    font-size: 22px;
    font-weight: 300;
    border: none;
    min-width: 400px;
    max-width: 400px;
    min-height: 200px;
    max-height: 200px;
  }
}

.button-box {
  .button {
    background: rgb(221, 54, 54);
    width: 400px;
    color: white;
    padding: 8px;
    font-size: 22px;
    margin: 0 auto;
    border-radius: 6px;
  }
}

.order-text {
  color: white;

  h1 {
    font-size: 54px;
    font-weight: 100;
    text-transform: uppercase;
  }

  p {
    font-size: 28px;
    width: 500px;
    margin: 50px auto;
  }

}

.other-services {
  text-transform: uppercase;
  padding: 15px;
  color: #2c3e50;
  background-color: white;
  margin: 20px auto;
  border-radius: 5px;
  width: 290px;
  font-size: 18px;
}

.order-container {
  padding-top: 100px;
  padding-bottom: 100px;
}

.contacts {
  min-height: 450px;
}

.contacts-row {
  display: flex;
  flex-direction: row;

  .contacts-column {
    width: 50%;
  }
}

.contacts-container{
  padding-top: 50px;
  .contacts-block {
    margin-bottom: 50px;
    font-size: 22px;
    h4 {
      font-size: 26px;
    }
    a {
      color: #2c3e50;
    }
  }
}

.footer {
  color: white;
  background: rgb(221, 54, 54);
  font-weight: 100;
  font-size: 20px;
  padding: 35px;
}
</style>
