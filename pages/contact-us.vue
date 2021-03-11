<template>
  <div>
    <header>
      <a href="#" class="logo"></a>
      <div class="burger-btn" @click="menuStatus = !menuStatus">
        <div class="drop-menu" :class="{active: menuStatus}">
          <n-link to="/">Main</n-link>
          <n-link to="/contact-us">Contact US</n-link>
          <a href="#">Blog</a>
        </div>
      </div>
    </header>
    <div class="mini-wrapper">
      <section>
        <div class="container">
          <h2 class="alt">
            Contact Us
          </h2>
          <p class="alt">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod<br>tempor incididunt ut labore et dolore magna aliqua. 
          </p>
        </div>
      </section>
    </div>
    <main class="contact-us">
      <div class="container">
        <div class="about-col">
          <img class="about-pic" src="/images/contact-image.svg">
          <div class="about-cell">
            <div class="about-title">
              ADDRESS
            </div> 
            <div class="about-message">
              Id convallis placerat sit sed duis id amet volutpat quam a, pharetra.
            </div>
          </div>
          <div class="about-cell">
            <div class="about-title">
              PHONE
            </div> 
            <div class="about-links">
              <a href="tel:+62-812-7313-4321" class="about-link phone">+62-812-7313-4321</a>
              <a href="tel:+62-817-000-1234" class="about-link phone">+62-817-000-1234</a>
            </div>
          </div>
          <div class="about-cell">
            <div class="about-title">
              ONLINE SERVICE
            </div> 
            <div class="about-links">
              <a href="http://www.afrianska.com" class="about-link url">www.afrianska.com</a>
              <a href="mailto:hello.afrian@gmail.com" class="about-link email">hello.afrian@gmail.com</a>
            </div>
          </div>
        </div>
        <form class="contact-form">
          <div class="form-title">
            Send us message
          </div>
          <div class="input-box">
            <label for="fullname">Full Name</label>
            <input type="text" id="fullname" placeholder="Your Name">
          </div>
          <div class="input-box">
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Your Email">
          </div>
          <div class="input-box">
            <label for="message">Message</label>
            <textarea id="message" placeholder="Your Message"></textarea>
          </div>

          <button class="form-button">Submit</button>
        </form>

        <div class="map-block" style="position:relative;overflow:hidden;"><a href="https://yandex.ru/maps/org/tsifrovoy_element/1340254435/?utm_medium=mapframe&utm_source=maps" style="color:#eee;font-size:12px;position:absolute;top:0px;">Цифровой Элемент</a><a href="https://yandex.ru/maps/56/chelyabinsk/category/internet_marketing/184105738/?utm_medium=mapframe&utm_source=maps" style="color:#eee;font-size:12px;position:absolute;top:14px;">Интернет-маркетинг в Челябинске</a><a href="https://yandex.ru/maps/56/chelyabinsk/category/web_design_studio/184105736/?utm_medium=mapframe&utm_source=maps" style="color:#eee;font-size:12px;position:absolute;top:28px;">Студия веб-дизайна в Челябинске</a><iframe src="https://yandex.ru/map-widget/v1/-/CCUQb-QBkB" width="100%" height="480" frameborder="0" allowfullscreen="true" style="position:relative;"></iframe></div>
      </div>
    </main>
    <footer>
      <div class="footer-box">
        <div class="container">
          <div class="f-banner">
            <div class="f-banner-col">
              <h2 class="alt">Intersted to work with our team?</h2>
              <p class="alt">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
            </div>
            <a href="#" class="button">Let’s Talk</a>
          </div>
          <div class="f-main">
            <div class="f-col">
              <a href="#" class="logo-alt">
                Afrianska
              </a>
              <table class="f-about-table">
                <tr>
                  <th>А.</th>
                  <td>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</td>
                </tr>
                <tr>
                  <th>T.</th>
                  <td>+62-812-7313-4321</td>
                </tr>
                <tr>
                  <th>E</th>
                  <td>hello.afrian@gmail.com</td>
                </tr>
              </table>
            </div>
            <div class="f-col">
              <div class="f-col-title">
                About US
              </div>
              <a href="#" class="f-link">About</a>
              <a href="#" class="f-link">What We Do</a>
              <a href="#" class="f-link">Project</a>
              <a href="#" class="f-link">How It Work With Us</a>
            </div>
            <div class="f-col">
              <div class="f-col-title">
                Follow US
              </div>
              <a href="#" class="f-link">Instagram</a>
              <a href="#" class="f-link">Facebook</a>
              <a href="#" class="f-link">LinkedIn</a>
              <a href="#" class="f-link">Youtube</a>
            </div>
            <div class="copyright">
              2019 © Afrianska. All rights reserved.
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      menuStatus: false
    }
  }
}
</script>

<style lang="scss">
@import '@/assets/main.scss';
</style>
