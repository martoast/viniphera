<template>
  <div>
    <video width="100%" height="100%" autoplay loop muted>
      <source src="/realsoap.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
    <b-container fluid>
      <b-row align-h="center" align-v="center">
        <b-col class="py-5" cols="12" md="6" sm="12">
          <h2 class="text-center py-3">Wine Soap</h2>
          <p class="px-2 px-md-3">
            The Heist Group consists of 3 women who find themselves at a
            crossroad. A drunk and impulsive night turned into risking
            everything they have and moving across the country in an attempt to
            change their lives. Little did they know how much their lives would
            actually change. Between terrible decisions and awful money
            management they find themselves having to choose between options..
            Continuing down the straight and narrow path, or getting into a life
            of crime. The choice is made for them when they accidentally (but
            almost by choice) kill a friend’s A$$hole boyfriend. After this
            horrific incident- there is no turning back.
          </p>
        </b-col>
        <b-col cols="12" md="6" sm="12">
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
  </div>
</template>

<script>
export default {};
</script>
