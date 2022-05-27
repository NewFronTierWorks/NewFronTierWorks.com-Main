<template>
  <v-container fill-height>
    <v-row class="text-center" dark height="70%">
      <v-col cols="12">
        <v-img
          :src="require('../assets/NFTW-Square-Logo.svg')"
          class="my-12"
          contain
          height="400"
        />
      </v-col>
    </v-row>
    <v-row height="30%">
      <v-col cols="12" lg="4" sm="12"
        ><v-card height="100%" class="pa-3 text-center" >
          <h1>ETHDenver 2020</h1>
          <v-row>
            <v-col cols="12" lg="3" sm="12"
              ><v-img
                :src="require('../assets/left-wing.svg')"
                class="ma-3"
                contain
            /></v-col>
            <v-col cols="12" lg="6" sm="12"
              >
              <p></p>
              <p>InterPlanetary Dao <br> Textile Bounty Winner</p>
              </v-col
            >
            <v-col cols="12" lg="3" sm="12"
              ><v-img
                :src="require('../assets/right-wing.svg')"
                class="ma-3"
                contain
            /></v-col>
          </v-row>
          
          
        </v-card></v-col
      >

      <v-col cols="12" lg="4" sm="12"
        ><v-card height="100%" class="pa-3 text-center" 
          ><h1>ETHDenver 2022 IRL</h1>
          <v-row>
            <v-col cols="12" lg="3" sm="12"
              ><v-img
                :src="require('../assets/left-wing.svg')"
                class="ma-3"
                contain
            /></v-col>
            <v-col cols="12" lg="6" sm="12"
              ><p class="mt-3">
                Colorado Jam Track <br />
                Top 30 Main Stage Winner
              </p>
              <p>Tableland Bounty Winner</p></v-col
            >
            <v-col cols="12" lg="3" sm="12"
              ><v-img
                :src="require('../assets/right-wing.svg')"
                class="ma-3"
                contain
            /></v-col>
          </v-row>
        </v-card></v-col
      >

      <v-col cols="12" lg="4" sm="12"
        ><v-card height="100%" class="pa-3 text-center"
          ><h1>ETHDenver 2022 Virtual</h1>
          <v-row>
            <v-col cols="12" lg="3" sm="12"
              ><v-img
                :src="require('../assets/left-wing.svg')"
                class="ma-3"
                contain
            /></v-col>
            <v-col cols="12" lg="6" sm="12"
              ><p class="mt-3">
                Colorado Jam Track <br />
                Top 30 Main Stage Winner
              </p>
              <p>Tableland Bounty Winner</p></v-col
            >
            <v-col cols="12" lg="3" sm="12"
              ><v-img
                :src="require('../assets/right-wing.svg')"
                class="ma-3"
                contain
            /></v-col>
          </v-row> 
          </v-card
      ></v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    ecosystem: [
      {
        text: "vuetify-loader",
        href: "https://github.com/vuetifyjs/vuetify-loader",
      },
      {
        text: "github",
        href: "https://github.com/vuetifyjs/vuetify",
      },
      {
        text: "awesome-vuetify",
        href: "https://github.com/vuetifyjs/awesome-vuetify",
      },
    ],
    importantLinks: [
      {
        text: "Documentation",
        href: "https://vuetifyjs.com",
      },
      {
        text: "Chat",
        href: "https://community.vuetifyjs.com",
      },
      {
        text: "Made with Vuetify",
        href: "https://madewithvuejs.com/vuetify",
      },
      {
        text: "Twitter",
        href: "https://twitter.com/vuetifyjs",
      },
      {
        text: "Articles",
        href: "https://medium.com/vuetify",
      },
    ],
    whatsNext: [
      {
        text: "Explore components",
        href: "https://vuetifyjs.com/components/api-explorer",
      },
      {
        text: "Select a layout",
        href: "https://vuetifyjs.com/getting-started/pre-made-layouts",
      },
      {
        text: "Frequently Asked Questions",
        href: "https://vuetifyjs.com/getting-started/frequently-asked-questions",
      },
    ],
  }),
};
</script>
