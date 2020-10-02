<template>
  <v-carousel>
    <v-carousel-item
      v-for="(item, i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    ></v-carousel-item>
  </v-carousel>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          src: 'https://imgur.com/7tYx958.png',
        },
        {
          src: 'https://imgur.com/7dVe9kd.png',
        },
        {
          src: 'https://imgur.com/DdjkDhY.png',
        },
        {
          src: 'https://imgur.com/ns2PgVY.png',
        },
      ],
    }
  },
}
</script>
<style></style>
