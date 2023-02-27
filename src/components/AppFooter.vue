<script>
export default {
  data() {
    return {
      title: "Footer",
    };
  },
};
</script>

<template>
  <footer>
    <div class="container">
      <!-- Prima lista -->
      <div>
        <h4 class="TitleUlFooter">DC COMICS</h4>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
        <h4 class="TitleUlFooter">Shop</h4>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>
      <!-- Prima lista -->

      <!-- Seconda lista -->
      <div>
        <h4 class="TitleUlFooter">DC</h4>
        <ul>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shops Help</li>
          <li>Contact Us</li>
        </ul>
      </div>
      <!-- Seconda lista -->

      <!-- Terza lista -->
      <div>
        <h4 class="TitleUlFooter">Sites</h4>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
      <!-- Terza lista -->
    </div>
  </footer>
</template>

<style scoped>
footer {
  background-image: url(../assets/img/footer-bg.jpg);
  background-position: center;
  background-size: cover;

  color: white;
}
.container {
  display: flex;
}

.container div {
  padding-top: 30px;
  padding-right: 50px;
}

h4 {
  margin-bottom: 10px;
}

div * {
  padding-bottom: 10px;
}

.TitleUlFooter {
  font-size: 20px;
}
</style>
