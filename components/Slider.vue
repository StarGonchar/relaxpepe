<template>
  <splide :options="options">
    <splide-slide
      v-for="({ title, description, img, link }, index) in slides"
      :key="index"
    >
      <a class="slide-box" :href="link" target="_blank">
        <img :src="require(`~/assets/img/pepe/${img}`)" />
        <h3>{{ title }}</h3>
        <p>{{ description }}</p>
      </a>
    </splide-slide>
  </splide>
</template>

<script>
export default {
  data() {
    return {
      slides: [
        {
          title: 'Relax Pepe #001',
          description: 'Original Relax Pepe',
          img: '1.svg',
          link: 'https://google.com',
        },
        {
          title: 'Relax Pepe #001',
          description: 'Original Relax Pepe',
          img: '1.svg',
          link: '#',
        },
        {
          title: 'Relax Pepe #001',
          description: 'Original Relax Pepe',
          img: '1.svg',
          link: '#',
        },
      ],
      options: {
        type: 'loop',
        perPage: 3,
        pagination: false,
        arrow: true,
        width: 1023,
        arrowPath: 'M16.5,11l9,9-9,9',
        breakpoints: {
          575: {
            perPage: 1,
            width: '100%',
            arrows: false,
          },
          991: {
            perPage: 1,
            width: 346,
            arrows: true,
          },
          1300: {
            perPage: 2,
            width: 682,
            arrows: true,
          },
        },
      },
    }
  },
}
</script>
