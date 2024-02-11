<script>
export default {
  name: "App",
  data() {
    return {
      message: "Hello",
    };
  },
};
</script>

<template>
  <footer>
    <div class="top">
      <div class="container">
        <div class="row">
          <div class="col-2">
            <h4>Dc Comics</h4>
            <ul class="list-unstyled">
              <li>
                <a> Characters </a>
              </li>
              <li>
                <a> Comics </a>
              </li>
              <li>
                <a> Movies </a>
              </li>
              <li>
                <a> TV </a>
              </li>
              <li>
                <a> Games </a>
              </li>
              <li>
                <a> Videos </a>
              </li>
              <li>
                <a> News </a>
              </li>
            </ul>

            <h4>Shop</h4>
            <ul class="list-unstyled">
              <li>
                <a> Shop DC </a>
              </li>
              <li>
                <a> Shop Dc Collectibles </a>
              </li>
            </ul>
          </div>
          <div class="col-2">
            <h4>Dc</h4>
            <ul class="list-unstyled">
              <li>
                <a> Terms of Use </a>
              </li>
              <li>
                <a> Privacy Policy (New) </a>
              </li>
              <li>
                <a> Ad Choices </a>
              </li>
              <li>
                <a> Advertising </a>
              </li>
              <li>
                <a> Jobs </a>
              </li>
              <li>
                <a> Subscriptions </a>
              </li>
              <li>
                <a> Talent Workshops </a>
              </li>
              <li>
                <a> CPSC Certificates </a>
              </li>
              <li>
                <a> Ratings </a>
              </li>
              <li>
                <a> Shop Help </a>
              </li>
              <li>
                <a> Contact Us </a>
              </li>
            </ul>
          </div>
          <div class="col-2">
            <h4>Sites</h4>
            <ul class="list-unstyled">
              <li>
                <a> DC </a>
              </li>
              <li>
                <a> MAD Magazines </a>
              </li>
              <li>
                <a> DC Kids </a>
              </li>
              <li>
                <a> DC Universe </a>
              </li>
              <li>
                <a> DC Power Visa </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="bottom">
      <div class="container">
        <a href="#" class="signup">Signup now!</a>
        <div class="social">
          <strong>Follow us</strong>
          <a href="">
            <img src="/img/footer-twitter.png" alt="" />
          </a>
          <a href="">
            <img src="/img/footer-facebook.png" alt="" />
          </a>
          <a href="">
            <img src="/img/footer-periscope.png" alt="" />
          </a>
          <a href="">
            <img src="/img/footer-pinterest.png" alt="" />
          </a>
          <a href="">
            <img src="/img/footer-youtube.png" alt="" />
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>
<style scoped>
footer {
  & > .top {
    background-image: url("/img/dc-logo-bg.png"), url("/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: 500px, cover;
    background-position: 80%, top;

    & h4 {
      color: var(--dc-light);
      margin: 1.5rem 0;
      text-transform: uppercase;
    }

    & ul a {
      color: gray;
      line-height: 1.5rem;
      font-size: 0.9rem;
    }
  }

  & > .bottom {
    padding: 1.5rem 0;

    & .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    & .signup {
      border: 1px solid var(--dc-primary);
      padding: 0.75rem;
      color: var(--dc-light);
      text-transform: uppercase;
    }
    & .social {
      display: flex;
      align-items: center;
      gap: 1rem;

      & strong {
        text-transform: uppercase;
        color: var(--dc-primary);
      }
    }
  }
}
</style>
