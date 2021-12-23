<template>
  <section class="container">
    <div class="mainBlock">
      <div class="tinkLogo">
        <img src="/images/retrotinklogo.webp" alt="RetroTink Logo" />
      </div>
      <h1 class="title">TinkSettings.Com</h1>
      <p class="subtitle">
        Settings Depository for the RetroTink Family of Products.
      </p>
      <p class="introText">
        To start, check out the <a href="/settings">Console Settings</a> page.
      </p>
      <div class="tinkLinks">
        <a href="https://www.retrotink.com/product-page/5x-pro"
          ><img src="/images/5x.webp" alt="RetroTink 5X Purchase Link" />
          <p>RetroTink 5x</p></a
        >
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.tinkLogo img {
  margin-top: 150px;
  max-width: 500px;
}

.tinkLinks {
  margin-top: 50px;
}

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 50px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 22px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.tinkLogo {
  max-width: 300px;
  margin-bottom: 50px;
}
</style>
