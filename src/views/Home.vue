<template>
  <v-app :style="{ background: $vuetify.theme.themes.light.background }">
    <v-row>
      <v-col md="3">
        <v-app :style="{ background: $vuetify.theme.themes.light.background }">
          <v-container>
            <v-col>
              <v-card class="text-center mt-8" shaped elevation="10">
                <v-avatar class="mt-n7" size="60" elevation="10">
                  <v-img src="../assets/img_avatar2.png"></v-img>
                </v-avatar>
                <v-card-title class="row justify-center"
                  >Bes Willis</v-card-title
                >
                <v-card-subtitle class="row justify-center"
                  >24 year, California</v-card-subtitle
                >
                <v-list class="mt-n5">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken"
                      >Blood</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken"
                      >Height</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken"
                      >Weight</v-list-item-title
                    >
                  </v-list-item>
                  <v-list-item class="mt-5">
                    <v-list-item-subtitle>-B</v-list-item-subtitle>
                    <v-list-item-subtitle>170 cm</v-list-item-subtitle>
                    <v-list-item-subtitle>60 Kg</v-list-item-subtitle>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-col>
            <v-col>
              <v-card class="mt-5 mt-n2" shaped elevation="10">
                <v-list>
                  <v-list-item>
                    <v-list-item-avatar size="10" color="cyan darken-1">
                    </v-list-item-avatar>
                    <v-list-item-title class="m1-n2">Kognum</v-list-item-title>
                    <v-list-item-subtitle>10 mg</v-list-item-subtitle>
                  </v-list-item>
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1"
                      >MON</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken-1"
                      >WED</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken-1"
                      >FRI</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken-1"
                      >SUN</v-list-item-title
                    >
                  </v-list-item>
                  <v-list-item class="mt-n5">
                    <v-list-item-subtitle
                      >2 times in a day before food</v-list-item-subtitle
                    >
                  </v-list-item>
                  <v-divider></v-divider>
                </v-list>
                <v-list two-line="" subheader="">
                  <v-list-item>
                    <v-list-item-avatar size="35">
                      <v-img src="../assets/logo.png"></v-img>
                    </v-list-item-avatar>
                    <v-list-item-content class="mr-n5">
                      <v-list-item-title
                        >Dr. Isabella Bowers.</v-list-item-title
                      >
                      <v-list-item-subtitle
                        >California Hospital Medical</v-list-item-subtitle
                      >
                    </v-list-item-content>
                  </v-list-item>
                </v-list>
                <v-list two-line="" subheader="" class="mt-n5">
                  <v-list-item>
                    <v-list-item-title>Surgeon</v-list-item-title>
                    <v-list-item-subtitle>spinal pain</v-list-item-subtitle>
                  </v-list-item>
                </v-list>
                <v-list two-line="" subheader="" class="my-n8">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1"
                      >Surgeon</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken-1"
                      >time</v-list-item-title
                    >
                  </v-list-item>
                  <v-list-item class="mt-n10">
                    <v-list-item-title class="cyan--text text--darken-1"
                      >26 Aug 2019</v-list-item-title
                    >
                    <v-list-item-title class="cyan--text text--darken-1"
                      >12:45</v-list-item-title
                    >
                  </v-list-item>
                </v-list>
              </v-card>
            </v-col>
            <v-col>
              <v-card class="text-center mt-6" shaped="" elevation="10">
                <v-list-item three-line="">
                  <v-list-item-content>
                    <v-list-item-title class="headline mb-1">
                      <v-icon>fab fa-cc-visa</v-icon>
                    </v-list-item-title>
                    <v-list-item-subtitle>
                      2345 4546 7889 5432</v-list-item-subtitle
                    >
                  </v-list-item-content>
                  <v-list-item-content>
                    <v-list-item-avatar
                      size="60"
                      style="max-width: 60px; margin-left: auto;"
                      color="cyan darken-1"
                    >
                      <v-icon color="white">fas fa-plus</v-icon>
                    </v-list-item-avatar>
                  </v-list-item-content>
                </v-list-item>
              </v-card>
            </v-col>
          </v-container>
        </v-app>
      </v-col>
      <v-col md="9">
        <v-app
          :style="{ background: $vuetify.theme.themes.dark.background }"
          class="rounded"
        >
          <v-container>
            <v-col>
              <v-list class="mt-5">
                <v-list-item>
                  <v-list-item-title class="cyn--text text--darken-1">
                    Examinations
                  </v-list-item-title>
                  <v-list-item-action>
                    <v-btn class="ma-2" tile outlined="" color="cyan darken-1">
                      <v-icon left>fas fa-eye</v-icon> See ALL
                    </v-btn>
                  </v-list-item-action>
                </v-list-item>
              </v-list>
            </v-col>

            <v-col>
              <v-row no-gutters>
                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card height="80px" width="10px" color="green"></v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader="" class="m1-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle
                              >21 Jul, 2019</v-list-item-subtitle
                            >
                            <v-list-item-title
                              >Hypertensive crisis</v-list-item-title
                            >
                            <v-list-item-subtitle
                              >Ongoing tratment</v-list-item-subtitle
                            >
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>
                <v-col class="mt-12">
                  <v-row no-gutters="">
                    <v-col cols="12" md="8">
                      <v-col>
                        <v-list class="mt-5">
                          <v-list-item>
                            <v-list-item-title class="cyan--text text--darken-1"
                              >Health Curve</v-list-item-title
                            >
                            <v-list-item-content>
                              <v-btn
                                class="mr-1"
                                outlined=""
                                color="cyan darken-1"
                                >D</v-btn
                              >
                            </v-list-item-content>
                            <v-list-item-content>
                              <v-btn
                                class="mr-1"
                                outlined=""
                                color="cyan darken-1"
                                >M</v-btn
                              >
                            </v-list-item-content>
                            <v-list-item-content>
                              <v-btn
                                class="mr-1"
                                outlined=""
                                color="cyan darken-1"
                                >Y</v-btn
                              >
                            </v-list-item-content>
                            <v-list-item-content>
                              <v-btn outlined="" color="cyan darken-1">D</v-btn>
                            </v-list-item-content>
                          </v-list-item>
                        </v-list>
                      </v-col>
                      <v-col>
                        <v-sparkline
                          :value="value"
                          :gradient="gradient"
                          :smooth="radius || flase"
                          :padding="padding"
                          :line-width="width"
                          :stroke-linCap="lineCap"
                          :gradient-direction="gradientDirection"
                          :fill="fill"
                          :type="type"
                          :auto-line-width="autoLineWidth"
                          auto-draw=""
                        >
                        </v-sparkline>
                      </v-col>
                    </v-col>
                  </v-row>
                </v-col>
              </v-row>
            </v-col>
          </v-container>
        </v-app>
      </v-col>
    </v-row>
  </v-app>
</template>

<script>
const gradients = [
  ['#222'],
  ['#42b3f4'],
  ['red', 'orange', 'yellow'],
  ['purple', 'violet'],
  ['#00c6ff', '#f0f', '#ff0'],
  ['#f72047', '#ffd200', '#1feaea'],
]
export default {
  name: 'Home',
  data: () => ({
    width: 2,
    radius: 10,
    padding: 8,
    lineCap: 'round',
    gradient: gradients[5],
    value: [0, 2, 5, 9, 5, 10, 3, 5, 0, 0, 1, 8, 2, 9, 0],
    gradientDirection: 'top',
    gradients,
    fill: false,
    type: 'trend',
    autoLineWidth: false,
    arrayEvents: null,
    date: new Date().toISOString().substring(0, 10),
  }),
  computed: {
    theme() {
      return this.$vuetify.theme.dark ? 'dark' : 'light'
    },
  },
  mounted() {
    this.arrayEvents = [...Array(6)].map(() => {
      const day = Math.floor(Math.random() * 30)
      const d = new Date()
      d.setDate(day)
      return d.toISOString().substring(0, 10)
    })
  },
  methods: {
    functionEvents(date) {
      const [, , day] = date.split('-')
      if ([12, 17, 28].includes(parseInt(day, 10))) return true
      if ([1, 19, 22].includes(parseInt(day, 10))) return ['red', '#00f']
      return false
    },
  },
}
</script>

<style scoped>
.rounded {
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
}
</style>
