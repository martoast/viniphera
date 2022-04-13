<template>
   <div>

     
     <div style="background: linear-gradient(90deg, rgba(153,86,153,1) 0%, rgba(60,4,88,1) 100%); height:100vh;">
          <b-navbar type="light">
         <b-navbar-brand href="#">
            <img width="50%" src="/logo2.png" alt="logo">
         </b-navbar-brand>
      </b-navbar>
        <b-container>
        <b-row  align-h="center" align-v="center" style="height:85vh;">
         <b-col cols="12" md="6" sm="12">
            <b-img src="/together.png" fluid alt="Responsive image"></b-img>
         </b-col>
         <b-col class="text-white" cols="12" md="6" sm="12">
            <h1
               style="font-family: 'Athiti';"
               >
               From Nature To Your Skin
            </h1>
            <h3 style="font-family: 'Athiti'">
               Naturally produced Soap Bars, free of
               sulfates/parabens and not tested on animals.
            </h3>
         </b-col>
      </b-row>
     </b-container>

     </div>
     

     
      <b-container class="text-center py-5" >
         <b-row align-h="center"  align-v="center" no-gutters>
            <b-col class="py-5" md="4" cols="12">
               <b-row  no-gutters>
                  <b-col>
                     <img style="max-width: 50%;"  class="mx-2" src="/noanimaltesting.png"></img>
                     <div style="font-family: 'Athiti'; font-size: 28px;" class="font-weight-bold text-gray">Not Tested On Animals</div>
                     <div style="font-family: 'Athiti'; font-size: 22px;">We stronly believe in producing a "cruilty free" soap that is safe for all types of skin. </div>
                  </b-col>
               </b-row>
            </b-col>
            <b-col class="py-5" md="4" cols="12">
               <div style="align-items: center; justify-content: center;">
                  <b-row  no-gutters>
                     <b-col>
                        <img style="max-width: 55%;" class="mx-2" src="/sulfatefree.png"></img>
                        <div style="font-family: 'Athiti'; font-size: 28px;" class="font-weight-bold text-gray">Free of Sulfates and Prabens</div>
                        <div style="font-family: 'Athiti'; font-size: 22px;">Our naturally produced soaps provide your skin the nourishment and moisturising it decerves with out the need of added artificial chemicals.</div>
                     </b-col>
                  </b-row>
               </div>
            </b-col>
            <b-col class="py-5" md="4" cols="12">
               <div style="align-items: center; justify-content: center;">
                  <b-row  no-gutters>
                     <b-col>
                        <img style="max-width: 50%;" class="mx-2" src="/madeinmexico.jpeg"></img>
                        <div style="font-family: 'Athiti'; font-size: 28px;">100% Made in Mexico</div>
                        <div style="font-family: 'Athiti'; font-size: 22px;">Produced in Ensenada Baja California with locally sourced ingredients. </div>
                     </b-col>
                  </b-row>
               </div>
            </b-col>
         </b-row>
      </b-container>
      <b-container class="py-2 py-md-5">
         <b-row align-h="center" align-v="center">
            <b-col class="py-5" cols="12" md="6" sm="12" >
               <h2
                  class="text-center py-3"
                  style="font-family: 'Athiti'; color: purple"
                  >
                  A New Kind Of Soap
               </h2>
               <p>
                  Thanks to the fact that grape seed oil contains a hundred times more
                  polyphenols and antioxidants than vitamin E and is so rich in
                  tannins. Our soap protects the fibers of the skin, detoxifies
                  tissues and improves circulation, helping reduce skin ageing marks
                  while providing a nourishing sking hydration to will keep your skin
                  healthy.
               </p>
               <p>
                  The name of Viníphera comes from one of the main ingredients in our
                  soaps, the vitis vinifera. We were inspired to change the letter "F"
                  for "PH" because our soaps proudly contain a neutral pH.
               </p>
            </b-col>
            <b-col cols="12" md="6" sm="12" >
               <b-card
                  img-src="/winesoap.png"
                  style="max-width: 40rem"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
            </b-col>
         </b-row>
      </b-container>
      <b-container class="py-5 d-none d-md-block">
         <h1 class="text-center" style="font-family: 'Allura'; color: purple">Products</h1>
         <b-card-group columns>
            <b-card
               img-src="/winesoap2.png"
               img-alt="Image"
               class="border-0"
               style="cursor: pointer;"
               overlay
               ></b-card>
            <b-card
               img-src="/olivesoap.png"
               img-alt="Image"
               class="border-0"
               style="cursor: pointer;"
               overlay
               ></b-card>
            <b-card
               img-src="/mintsoap.png"
               img-alt="Image"
               class="border-0"
               style="cursor: pointer;"
               overlay
               ></b-card>
            <b-card
               img-src="/charcoalsoap.png"
               img-alt="Image"
               class="border-0"
               style="cursor: pointer;"
               overlay
               ></b-card>
            <b-card
               img-src="/oatmealmilk.png"
               img-alt="Image"
               class="border-0"
               style="cursor: pointer;"
               overlay
               ></b-card>
            <b-card
               img-src="/lavandersoap.png"
               img-alt="Image"
               class="border-0"
               style="cursor: pointer;"
               overlay
               ></b-card>
         </b-card-group>
      </b-container>
      <b-container class="d-block d-md-none">
         <h1 class="text-center" style="font-family: 'Allura'; color: purple">Products</h1>
         <b-carousel
            id="carousel-fade"
            style="text-shadow: 0px 0px 2px #000"
            fade
            indicators
            >
            <b-carousel-slide
               img-src="/winesoap2.png"
               ></b-carousel-slide>
            <b-carousel-slide
               img-src="/lavandersoap.png"
               ></b-carousel-slide>
            <b-carousel-slide
               img-src="/oatmealmilk.png"
               ></b-carousel-slide>
            <b-carousel-slide
               img-src="/charcoalsoap.png"
               ></b-carousel-slide>
         </b-carousel>
      </b-container>
      <b-container class="py-5">
         <b-row align-v="center">
            <b-col cols="12" md="6" sm="12" >
               <b-card
                  img-src="/ceo.png"
                  img-alt="Image"
                  class="border-0"
                  overlay
                  ></b-card>
            </b-col>
            <b-col class="pt-3" cols="12" md="6" sm="12" >
               <h1 style="text-align: center; font-family: 'Allura'; color: purple">
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
      <b-container fluid class="text-center text-white" style="background-color: rgb(153, 86, 153);">
         <b-row class="p-4" align-v="center" align-h="center">
            <b-col cols="12" md="auto" sm="12" class="mr-auto p-3 px-md-5">
               <div class="d-block d-md-none py-3">
                  <b-btn class="p-0" href="//twitter.com/theheistworld" variant="link">
                     <img  class="mx-2" src="/mobile/insta.svg"></img>
                  </b-btn>
                  <b-btn class="p-0" href="//www.facebook.com/viniphera" variant="link">
                     <img  class="mx-1" src="/mobile/facebook.svg"></img>
                  </b-btn>
                  <b-btn class="p-0" href="//opensea.io/collection/the-heist-collection" variant="link">
                     <img  class="mx-2" src="/mobile/amazon.svg"></img>
                  </b-btn>
               </div>
               <img class="mx-2" src="/logo.png"></img>
            </b-col>
            <b-col cols="12" md="auto" sm="12" class="ml-auto "
               >
               <div class="d-none d-md-block">
                  <b-btn class="p-0" href="//twitter.com/theheistworld" variant="link">
                     <img  class="mx-2" src="/mobile/insta.svg"></img>
                  </b-btn>
                  <b-btn class="p-0" href="//www.facebook.com/viniphera" variant="link">
                     <img  class="mx-1" src="/mobile/facebook.svg"></img>
                  </b-btn>
                  <b-btn class="p-0" href="//opensea.io/collection/the-heist-collection" variant="link">
                     <img  class="mx-2" src="/mobile/amazon.svg"></img>
                  </b-btn>
               </div>
            </b-col>
         </b-row>
      </b-container>
   </div>
</template>

<script>
export default {
   data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
};
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
