<template>
  <v-app :style="{ background: $vuetify.theme.themes.light.background }">
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
      d.setData(day)
      return d.toISOString().substring(0, 10)
    })
    console.log(this.arrayEvents)
  },
  methods: {
    functionEvents(date) {
      const [, , day] = date.split('-')
    },
  },
}
</script>
