<template>
  <div>
    <div class="main-wrapper">
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
      <section>
        <div class="container">
          <h1 class="alt">
            New Automation<br>
            Tool for Your Home
          </h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing<br>elit. Faucibus tristique vulputate ultrices ut mauris<br>tellus at. Posuere sollicitudin odio tellus elit.
          </p>
          <a href="#" class="button">See Our Project</a>
        </div>
      </section>
    </div>
    <main>
      <div class="container">
        <div class="info-grid">
          <h2 class="info-title">
            What we do to help<br>
            our client grow in<br>
            digital era,
          </h2>
          <a href="#" class="info-card" data-card="1">
            <div class="info-card-pic-box">
            <div class="info-card-pic"></div>
            </div>
            <div class="info-card-title">
              Bring Technology To Your 
              Comfrotable Home
            </div>
            <div class="info-card-description">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
            </div>
            <div href="#" class="info-card-action">
              Learn more
            </div>
          </a>
          <a href="#" class="info-card" data-card="2">
            <div class="info-card-pic"></div>
            <div class="info-card-title">
              Make Your business To Be Better Famous In Internet
            </div>
            <div class="info-card-description">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
            </div>
            <div href="#" class="info-card-action">
              Learn more
            </div>
          </a>
          <a href="#" class="info-card" data-card="3">
            <div class="info-card-pic"></div>
            <div class="info-card-title">
              Build Your Digital Product That Suitable For Your Need
            </div>
            <div class="info-card-description">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
            </div>
            <div class="info-card-action">
              Learn more
            </div>
          </a>
        </div>
      </div>
    </main>
    <footer>
      <div class="pre-footer">
        <div class="container">
          <div class="info">
            <h2 class="alt">Our Beloved<br>Client</h2>
            <p class="alt">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
          </div>
          <table class="partners">
            <tr>
              <td>
                <a href="#" class="partners-item">
                  LOGO CLIENT 1
                </a>
              </td>
              <td>
                <a href="#" class="partners-item">
                  LOGO CLIENT 2
                </a>
              </td>
              <td>
                <a href="#" class="partners-item">
                  LOGO CLIENT 3
                </a>
              </td>
              <td>
                <a href="#" class="partners-item">
                  LOGO CLIENT 4
                </a>
              </td>
            </tr>
            <tr>
              <td>
                <a href="#" class="partners-item">
                  LOGO CLIENT 5
                </a>
              </td>
              <td>
                <a href="#" class="partners-item">
                  LOGO CLIENT 6
                </a>
              </td>
              <td>
                <a href="#" class="partners-item">
                  LOGO CLIENT 7
                </a>
              </td>
              <td>
                <a href="#" class="partners-item">
                  More Client
                </a>
              </td>
            </tr>
          </table>
        </div>
      </div>
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
