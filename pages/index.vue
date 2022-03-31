<template>
  <div>
    <video width="100%" height="100%" autoplay playsinline muted loop>
      <source src="/realvideo.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
    <b-container class="py-5">
      <h1 class="text-center" style="text-align: center; font-family: 'Athiti'">
        From Nature To Your Skin
      </h1>
      <h3 class="text-center" style="text-align: center; font-family: 'Athiti'">
        Naturally produced Soap Bars for skin care and personal hygiene, free of
        sulfates and parabens, made 100% in Mexico with ingredients from the
        region; environmentally friendly and not tested on animals.
      </h3>
    </b-container>
    <b-container class="py-5">
      <b-row align-h="center" align-v="center">
        <b-col class="py-5" cols="12" md="6" sm="12">
          <h2 class="text-center py-3" style="font-family: 'Athiti'">
            A new kind of soap
          </h2>
          <p>
            The name of Viníphera comes from one of the main ingredients in our
            soaps, the vitis vinifera. We were inspired to change the letter "F"
            for "PH" since our soaps proudly contain a neutral pH.
          </p>
          <p>
            Innovative technique that deeply hydrates and nourishes the skin,
            thanks to the fact that grape seed oil contains a hundred times more
            polyphenols and antioxidants than vitamin E, it is also rich in
            tannins that contribute to skin rejuvenation, protects the fibers of
            the skin support, detoxifies tissues and improves circulation, helps
            reduce skin marks and expression lines, tone and firm the skin
            contributing to the youth of the body, keeping it healthy and
            therefore beautiful.
          </p>
        </b-col>
        <b-col cols="12" md="6" sm="12">
          <b-card
            img-src="/logo-hoja.png"
            style="max-width: 40rem"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
        </b-col>
      </b-row>
    </b-container>
    <b-container class="py-5">
      <b-row align-v="center">
        <b-col cols="12" md="6" sm="12">
          <b-card
            img-src="/ceo.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
        </b-col>
        <b-col cols="12" md="6" sm="12">
          <h1
            class="text-primary"
            style="text-align: center; font-family: 'Allura'"
          >
            Alejandra Correa Terán.
          </h1>
          <h3
            style="text-align: center; font-size: 31px; font-family: 'Athiti'"
          >
            Founder & CEO
          </h3>
          <p style="text-align: center">
            My name is Alejandra Correa Terán, I am the founder and CEO of
            Viníphera. The idea for Viníphera began with a trip I made to Spain
            in 2007, in which I was introduced to the world of wine therapy, I
            already had prior knowledge of soap making; Upon returning to
            Mexico, finding myself right in the Valle de Guadalupe, seeing
            everything that nature provides us and is produced on the Wine
            Route, realizing the needs of the inhabitants, I decide to start
            with the production of wine therapy soaps.
          </p>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
@font-face {
  font-family: "Allura";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/Allura.ttf") format("truetype");
}

@font-face {
  font-family: "Athiti";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("~assets/fonts/Athiti.ttf") format("truetype");
}
</style>
