<script lang="ts">
  import Home from "@layouts/Home.svelte";
  import Showcase from "@layouts/Showcase.svelte";
  import Footer from "@layouts/Footer.svelte";
  import ScrollTop from "lib/base/ScrollTop.svelte";
</script>

<main>
  <ScrollTop />
  <Home />
  <Showcase />
  <Footer />
</main>

<style>
  :root {
    --dark: #222831;
    --navy: #30475e;
    --red: #f05454;
    --gray: #dddddd;
    --light: #f0f0f0;
  }

  @font-face {
    font-family: "SQ Market";
    src: url("//db.onlinewebfonts.com/t/e1aad591ec868e33cf9363b2a4af103c.eot");
    src: url("//db.onlinewebfonts.com/t/e1aad591ec868e33cf9363b2a4af103c.eot?#iefix")
        format("embedded-opentype"),
      url("//db.onlinewebfonts.com/t/e1aad591ec868e33cf9363b2a4af103c.woff2")
        format("woff2"),
      url("//db.onlinewebfonts.com/t/e1aad591ec868e33cf9363b2a4af103c.woff")
        format("woff"),
      url("//db.onlinewebfonts.com/t/e1aad591ec868e33cf9363b2a4af103c.ttf")
        format("truetype"),
      url("//db.onlinewebfonts.com/t/e1aad591ec868e33cf9363b2a4af103c.svg#SQ Market Thin")
        format("svg");
    font-weight: 200;
  }

  @font-face {
    font-family: "SQ Market";
    src: url("//db.onlinewebfonts.com/t/ea4f956bace1d9f1f1a5121418cdfad9.eot");
    src: url("//db.onlinewebfonts.com/t/ea4f956bace1d9f1f1a5121418cdfad9.eot?#iefix")
        format("embedded-opentype"),
      url("//db.onlinewebfonts.com/t/ea4f956bace1d9f1f1a5121418cdfad9.woff2")
        format("woff2"),
      url("//db.onlinewebfonts.com/t/ea4f956bace1d9f1f1a5121418cdfad9.woff")
        format("woff"),
      url("//db.onlinewebfonts.com/t/ea4f956bace1d9f1f1a5121418cdfad9.ttf")
        format("truetype"),
      url("//db.onlinewebfonts.com/t/ea4f956bace1d9f1f1a5121418cdfad9.svg#SQ Market Light")
        format("svg");
    font-weight: 300;
  }

  @font-face {
    font-family: "SQ Market";
    src: url("//db.onlinewebfonts.com/t/cc1fd3ac8497388cfc4da587e06951b0.eot");
    src: url("//db.onlinewebfonts.com/t/cc1fd3ac8497388cfc4da587e06951b0.eot?#iefix")
        format("embedded-opentype"),
      url("//db.onlinewebfonts.com/t/cc1fd3ac8497388cfc4da587e06951b0.woff2")
        format("woff2"),
      url("//db.onlinewebfonts.com/t/cc1fd3ac8497388cfc4da587e06951b0.woff")
        format("woff"),
      url("//db.onlinewebfonts.com/t/cc1fd3ac8497388cfc4da587e06951b0.ttf")
        format("truetype"),
      url("//db.onlinewebfonts.com/t/cc1fd3ac8497388cfc4da587e06951b0.svg#SQ Market Regular")
        format("svg");
    font-weight: 400;
  }

  @font-face {
    font-family: "SQ Market";
    src: url("//db.onlinewebfonts.com/t/ff88ec76adf16430abbf0af2fbd66031.eot");
    src: url("//db.onlinewebfonts.com/t/ff88ec76adf16430abbf0af2fbd66031.eot?#iefix")
        format("embedded-opentype"),
      url("//db.onlinewebfonts.com/t/ff88ec76adf16430abbf0af2fbd66031.woff2")
        format("woff2"),
      url("//db.onlinewebfonts.com/t/ff88ec76adf16430abbf0af2fbd66031.woff")
        format("woff"),
      url("//db.onlinewebfonts.com/t/ff88ec76adf16430abbf0af2fbd66031.ttf")
        format("truetype"),
      url("//db.onlinewebfonts.com/t/ff88ec76adf16430abbf0af2fbd66031.svg#SQ Market Medium")
        format("svg");
    font-weight: 500;
  }

  @font-face {
    font-family: "SQ Market";
    src: url("//db.onlinewebfonts.com/t/2ac675ffd4e74e220f042c88e292a392.eot");
    src: url("//db.onlinewebfonts.com/t/2ac675ffd4e74e220f042c88e292a392.eot?#iefix")
        format("embedded-opentype"),
      url("//db.onlinewebfonts.com/t/2ac675ffd4e74e220f042c88e292a392.woff2")
        format("woff2"),
      url("//db.onlinewebfonts.com/t/2ac675ffd4e74e220f042c88e292a392.woff")
        format("woff"),
      url("//db.onlinewebfonts.com/t/2ac675ffd4e74e220f042c88e292a392.ttf")
        format("truetype"),
      url("//db.onlinewebfonts.com/t/2ac675ffd4e74e220f042c88e292a392.svg#SQ Market Bold")
        format("svg");
    font-weight: 600;
  }
  main {
    font-family: "SQ Market", sans-serif;
    overflow-x: hidden;
  }

  :global(body) {
    background-color: var(--light);
    color: var(--dark);
    transition: background-color 0.3s;
  }
  :global(body.dark-mode) {
    background-color: var(--dark);
    color: var(--gray);
  }
  :global(section) {
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  :global(.container) {
    height: 75vh;
    width: 60vw;
    align-items: center;
    display: flex;
    justify-content: center;
  }
  :global(.wrapper) {
    height: 100%;
    width: 100%;
    align-items: center;
    display: flex;
    justify-content: center;
  }
</style>
